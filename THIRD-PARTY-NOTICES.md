# Third-Party Notices / Üçüncü Taraf Bildirimleri

## English

Just Enough Guns (JEG), MigaMi; upstream credits: MrCrayfish, Bomb787, NineZero.
Source: https://github.com/MigaMiDev/Just-Enough-Guns
Imported baseline: JustEnoughGuns-0.14.5-1.20.1.jar, SHA-256
EEE06EE8D93756235F6A888D7A0B8E176B76CD7E209A154E27899359138F9908.
Its declaration is GNU GPLv3. The compound-bow audit found no separate restriction
for the imported bow model, animations or textures. Five unrelated ARR scope
models are outside that finding and are not authorized by this audit.
Imported bow geometry, animations, item resources, combat behavior and sound
references are credited to upstream, not claimed as new artwork.
JEG sounds carry a separate CC0 notice, preserved in SOUND-LICENSE.txt.

Modifications by Korkuluk, 2026-10-08 through 2026-10-10: standalone namespace,
combat and client integration, olive palette, custom sight, special-arrow variants,
recipes, quiver integration, HUD/icons, key integration and localization.
The exact original asset hashes are in upstream-assets.json; current resource
hashes and migration origins are in the release manifest.

TaCZ (Timeless and Classics Guns: Zero), Serene Wave Studio / Timeless Squad:
https://github.com/MCModderAnchor/TACZ
Code license: GNU GPL v3. Assets: CC BY-NC-ND 4.0, per the upstream notice.
The hit-marker texture is loaded from the user's installed TaCZ mod; no copy is
included here. BowHud's hit-marker drawing and BowImpactEffects timing were
adapted with reference to TaCZ RenderCrosshairEvent. Interaction-hint placement
was adapted with reference to InteractKeyTextOverlay. The smithing scroll mixin
is a local compatibility fix for the installed TaCZ screen.
Explosive arrows call the installed TaCZ explosion API; arrow selection uses
the installed TaCZ fire-mode keybinding, without bundling those implementations.

LesRaisins Tactical Equipments, LesRaisins Studio:
https://github.com/LesRaisins-Studios/LesRaisins-Tactical-Equipements
Code license: GNU GPL v3. Art assets: All Rights Reserved, per the upstream notice.
Local recipes use the installed mod's smithing category. The charge bar is drawn
locally and follows its visual style; no LesRaisins bar artwork is bundled.

The nocked arrow and quiver originated from the existing local
tachtical-modern-bow-forge-1.20.1-0.8.19.jar baseline. The arrow import used
assets/compoundbow/geo/modern_arrow.geo.json. Their original upstream author and
asset authorship is recorded from the project owner's statement on 2026-10-10:
the arrow and quiver were created by this project, not imported from a third-party
mod. Migration from an earlier local build does not imply third-party authorship.
The previous pending-provenance warning is withdrawn on that basis; this is an
owner declaration, not an independent authorship audit. This notice grants no
rights beyond the applicable original licenses.

## Türkçe

Just Enough Guns (JEG): MigaMi; özgün katkılar: MrCrayfish, Bomb787, NineZero.
Kaynak: https://github.com/MigaMiDev/Just-Enough-Guns
İçe aktarılan temel sürüm: JustEnoughGuns-0.14.5-1.20.1.jar. SHA-256:
EEE06EE8D93756235F6A888D7A0B8E176B76CD7E209A154E27899359138F9908.
Bu sürüm GNU GPLv3 beyan eder. Denetimde kullanılan yay modeli, animasyon ve
dokuları için ayrı kısıtlama bulunmadı. Beş ilgisiz dürbün modelinin ARR bildirimi
bu bulgudan ayrıdır; denetim onlara yeniden dağıtım hakkı vermez.
Özgün yay geometrisi, animasyonlar, eşya kaynakları, savaş davranışı ve ses
referansları upstream'e aittir; yeni çizilmiş eser olarak sunulmaz.
JEG sesleri ayrı CC0 bildirimi taşır; SOUND-LICENSE.txt özgün metni korur.

Korkuluk değişiklikleri, 2026-10-08 ile 2026-10-10: bağımsız kimlik, savaş ve
istemci entegrasyonu, zeytin yeşili palet, özel nişangah, ok çeşitleri, tarifler,
sadak entegrasyonu, HUD/ikonlar, tuş entegrasyonu ve dil desteği.
İlk kaynak hash kayıtları upstream-assets.json içindedir. Güncel kaynak hash
kayıtları ve eski paket kökenleri yayın manifestindedir.

TaCZ (Timeless and Classics Guns: Zero): Serene Wave Studio / Timeless Squad.
Kaynak: https://github.com/MCModderAnchor/TACZ
Kod GNU GPLv3; varlıklar upstream bildirimi uyarınca CC BY-NC-ND 4.0'dır.
İsabet işareti dokusu kurulu TaCZ'den okunur, bu pakete kopyalanmaz. İsabet işareti
çizimi/zamanlaması ve etkileşim uyarısı TaCZ kodu referans alınarak uyarlanmıştır.
Üretim ekranı kaydırma mixin'i yerel uyumluluk düzeltmesidir. Patlama kurulu
TaCZ'nin API'sini çağırır; atış modu tuşu kurulu TaCZ tuş atamasını kullanır.

LesRaisins Tactical Equipments: LesRaisins Studio.
Kaynak: https://github.com/LesRaisins-Studios/LesRaisins-Tactical-Equipements
Kod GNU GPLv3; sanat varlıkları upstream bildirimi uyarınca All Rights Reserved.
Yerel tarifler kurulu modun üretim kategorisini kullanır. Çekiş çubuğu yerel
olarak çizilir; LesRaisins çubuk görseli bu pakete kopyalanmaz.

Ok ve sadak mevcut yerel tachtical-modern-bow-forge-1.20.1-0.8.19.jar temelinden
gelir. Ok içe aktarımı assets/compoundbow/geo/modern_arrow.geo.json kullanmıştır.
Proje sahibinin 2026-10-10 tarihli beyanına göre ok ve sadak bu proje tarafından
üretilmiştir; üçüncü taraf bir moddan alınmamıştır. Önceki yerel sürümden aktarım,
üçüncü taraf yazarlığı anlamına gelmez. Önceki belirsiz kaynak uyarısı bu beyana
dayanarak kaldırılmıştır; bu kayıt bağımsız yazarlık denetimi değildir. Bu bildirim
özgün lisansların verdiğinin ötesinde bir hak tanımaz.

GPLv3'ün özgün İngilizce metni LICENSE-GPL-3.0.txt içindedir. Türkçe açıklamalar
bağlayıcı lisans metninin yerini almaz. CC0 ses bildiriminin özgün metni de korunur.
