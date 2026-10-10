# Upstream And Scope

Original: Just Enough Guns by MigaMi, based on work by MrCrayfish, Bomb787 and
NineZero. Source reference: https://github.com/MigaMiDev/Just-Enough-Guns

Runtime baseline is the locally installed JustEnoughGuns-0.14.5-1.20.1.jar.
The fetched source repository reports 0.14.0 in build.gradle; it is reference
material, not proof that the installed binary matches it. The exact asset
provenance and SHA-256 hashes are recorded in upstream-assets.json.

This project uses a separate standalonebow namespace and does not load JEG.
The user's stable compoundbow mod is separate and must not be overwritten.
Required external mods: GeckoLib 4.8.4+ (4.x), Curios 5.14.1+ (5.x),
TaCZ 1.1.8 (1.1.x) and LesRaisins Tactical Equipments 0.4.3 (0.4.x).
Minecraft 1.20.1 and Forge 47.x are required. TaCZ and LesRaisins are required
for the intended smithing integration. The hit-marker texture is resolved from
the installed TaCZ mod and is not bundled in this mod.

The installed upstream declares GNU GPLv3. The exact JEG bow audit supports
GPL reuse of the imported bow assets without separate consent, subject to the
applicable GPL obligations. Preserve original attribution and the CC0 sound
notice. The project owner confirmed on 2026-10-10 that the migrated arrow and
quiver were created within this project. The earlier pending-provenance warning
is withdrawn on that basis. See THIRD-PARTY-NOTICES.md.

## Türkçe

Özgün yay: MigaMi'nin Just Enough Guns modu; katkılar MrCrayfish, Bomb787 ve
NineZero. Yerel temel 0.14.5'tir; referans kaynak deposu 0.14.0 bildirir ve aynı
ikili sürümün kanıtı değildir. Özgün hash kayıtları upstream-assets.json içindedir.
Mod bağımsız standalonebow kimliğini kullanır; JEG çalışma zamanı gerekmez.
Bağımlılık sürümleri ve iki dilli kurulum açıklaması README.md içindedir.
TaCZ isabet dokusu kurulu moddan okunur; burada kopyası dağıtılmaz.

JEG'nin bu yayına ait denetim, ayrı izin gerektirmeden GPL koşullarıyla yeniden
kullanımı destekler. Katkı kayıtları ve ayrı CC0 ses bildirimi korunmalıdır.
Proje sahibi 2026-10-10 tarihinde ok ve sadağın bu projede üretildiğini doğruladı.
Eski yerel paketten aktarım üçüncü taraf kaynağı değildir; önceki belirsizlik
uyarısı bu beyana dayanarak kaldırıldı. THIRD-PARTY-NOTICES.md dosyasına bakın.
Derleme ve hash kontrolü çok oyunculu/temiz istemci testinin yerini almaz.

Verification of asset hashes and Java compilation is not a certification of
in-game visual parity. Client fidelity and core integration reports identify
remaining behavior and test coverage gaps.

The historical verify-assets.ps1 and verify-package.ps1 scripts compare against
the initial upstream extraction, not the customized current model. Use
verify-current-package.ps1 for current packaging checks. A passing package check
does not replace clean-client or multiplayer gameplay tests.
