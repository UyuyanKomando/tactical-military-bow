# Kaynaktan Derleme / Building From Source

## Türkçe

Java 17 ve Gradle 8.8 gerekir. Kaynak ZIP'te `work/standalone-bow` klasörüne girin. GeckoLib 4.8.4 Forge 1.20.1 ve Curios 5.14.1 Forge 1.20.1 JAR'larını kendi resmi dağıtımlarından edinip `libs/geckolib-4.8.4.jar` ve `libs/curios-5.14.1.jar` adlarıyla koyun. Bağımlılık modlarının ikilileri bu kaynak paketine dahil edilmez. `DEPENDENCY-HASHES.json` kullanılan yerel dosyaların SHA-256 kayıtlarını içerir.

`gradle build --console=plain` çalıştırın. İlk derlemede ForgeGradle ve Minecraft bağımlılıkları için internet gerekir. Sonuç `build/libs/standalone-compound-bow-forge-1.20.1-0.1.0.jar` dosyasıdır. Yerel modelleri yeniden üretmek şart değildir; düzenlenebilir JSON/PNG kaynakları `src/main/resources` içindedir.

İsteğe bağlı model/ikon üretimi: Node.js ile `node integrate-arrow-assets.cjs`, Windows PowerShell ile `./create-arrow-icons.ps1`, ardından `node update-localizations.cjs` çalıştırın. Ok girdileri ZIP'in `outputs/arrow-preview` klasöründe; düzenlenebilir `.bbmodel` dosyaları da buradadır. `node verify-arrow-assets.cjs` tarif ve model hiyerarşisini doğrular. `update-reference-sight.cjs` yalnızca nişangah düzenlemesi içindir. `apply-olive-palette.ps1` tekrar tekrar uygulanmamalıdır; nihai PNG dosyalarını düzenleyin.

## English

Requires Java 17 and Gradle 8.8. Enter `work/standalone-bow` in the source ZIP. Obtain the official GeckoLib 4.8.4 Forge 1.20.1 and Curios 5.14.1 Forge 1.20.1 JARs and save them as `libs/geckolib-4.8.4.jar` and `libs/curios-5.14.1.jar`. Dependency mod binaries are not included in this source archive. `DEPENDENCY-HASHES.json` records the SHA-256 hashes of the local build dependencies.

Run `gradle build --console=plain`. The first build requires network access for ForgeGradle and Minecraft dependencies. Output: `build/libs/standalone-compound-bow-forge-1.20.1-0.1.0.jar`. Asset regeneration is optional; editable JSON/PNG sources are included under `src/main/resources`.

Optional model/icon generation: run `node integrate-arrow-assets.cjs` with Node.js, `./create-arrow-icons.ps1` with Windows PowerShell, then `node update-localizations.cjs`. Arrow inputs and editable `.bbmodel` files are in the ZIP's `outputs/arrow-preview` directory. `node verify-arrow-assets.cjs` validates recipes and model hierarchy. `update-reference-sight.cjs` is only for sight edits. Do not repeatedly apply `apply-olive-palette.ps1`; edit the final PNG sources instead.
