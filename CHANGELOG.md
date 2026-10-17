# Türkçe - 1.0.3

- Peş peşe atışlarda, yay tam çekilmiş görünmesine rağmen okun fırlamaması düzeltildi. Önceki atışın bekleme süresinde başlayan çekiş artık kaybolmaz; atış aralığı sınırı korunur.
- Tam çekiş süresi 1 saniyeden 0,7 saniyeye indirildi. Animasyon, dolum göstergesi ve hasar dolumu eşleştirildi; tam çekiş hasarı değişmedi.
- Yay tam çekili tutulurken oluşan tekrarlayan sallanma kaldırıldı.
- Mevcut TaCZ atış modu tuşuna (varsayılan G) bağımsız ok seçim çemberi eklendi. Tuşa basılı tutun, fareyle oku seçin ve tuşu bırakın.
- Çember beş ok türünün simgelerini ve stok sayılarını gösterir. Merkezde bırakmak veya Esc iptal eder; çekiş ve doldurma sırasında seçim yapılamaz.
- Arcana bağımlılığı yoktur. Bu özellik Arcana'nın kendi mühimmat menüsüne entegrasyon değildir.
- Tarifler, tam çekiş hasarları ve gerekli mod bağımlılıkları değişmedi.
- Çok oyunculuda istemci ve sunucuyu birlikte 1.0.3'e güncelleyin; ağ protokolü güncellendi.

# English - 1.0.3

- Fixed consecutive shots sometimes failing to fire despite appearing fully drawn. Draw requests started during the previous shot's cooldown are no longer lost; the shot interval limit remains enforced.
- Reduced full draw time from 1 second to 0.7 seconds. Animation, charge indicator and damage charge are synchronized; full-charge damage is unchanged.
- Removed the repeating bow sway while holding a full draw.
- Added a standalone arrow selection wheel using TaCZ's existing Fire Mode key (G by default). Hold the key, point at an arrow and release to select.
- The wheel displays all five arrow types with icons and ammo counts. Release in the center or press Esc to cancel; selection is blocked while drawing or reloading.
- Arcana is not required. This feature is not an integration with Arcana's native ammo menu.
- Recipes, full-charge damage and required mod dependencies are unchanged.
- Multiplayer clients and servers must both update to 1.0.3 because the network protocol has changed.

# 1.0.2 / Sürüm Notları / Release Notes

## Türkçe - 1.0.2

- Yay ikinci eldeyken oluşan hatalı birinci şahıs görüntüsü kaldırıldı.
- TaCZ tarzı sırtta taşıma eklendi: yay ikinci eldeyken veya ilk hotbar yuvasında seçili değilken sırtta görünür.
- İkinci el ve hotbar için sırttaki yay konumu ve açısı eşitlendi.
- Sadağın eksik gövde kaplaması düzeltildi.
- Nişangâh, siyah yuvarlak gövde, yan vidalar ve yeni menzil çizgileriyle yenilendi; V işareti kaldırıldı.
- Nişangâhın iç çizgileri ve mesafe yazıları parlak neon kırmızı yapıldı.
- Mevcut ok hasarları, tarifler ve atış davranışı korundu. Bağımlılıklar değişmedi.

## English - 1.0.2

- Fixed incorrect first-person rendering when the bow is in the offhand.
- Added TaCZ-style back carry: the bow appears on the back while in the offhand or in the first hotbar slot when that slot is not selected.
- Matched back carry position and angle between offhand and hotbar placement.
- Fixed a missing quiver body surface texture.
- Redesigned the sight with a black circular housing, side screws and new range markings; removed the V-shaped marker.
- Changed the range markings and distance labels to bright neon red.
- Existing arrow damage, recipes and firing behavior are unchanged. Dependencies are unchanged.

# 1.0.1 / Sürüm Notları / Release Notes

## Türkçe - 1.0.1

- Atışın tüm bakış yönlerinde doğru noktadan çizilmesi ve ilk saplanma konumunun eşzamanlanması düzeltildi.
- Ok gövdeleri uç tarafından %40 kısaltıldı; kuyruk konumu ve uç/tüy boyutları korundu.
- Saplandığı blok kırılan toplanabilir oklar eşya olarak düşer; yeniden saplanmaz.
- ItemPhysic Guns için isteğe bağlı yatay yer modeli uyumluluğu eklendi.
- Lava değen oklar yok olur; yalnızca patlayıcı ok patlar.
- Yaya özel dokuz büyü ve kitapları kaldırıldı; yay büyü masası veya örsle büyülenemez.
- Teknik mod kimliği `tacticalmilitarybow` oldu; eski kayıtlar için geçiş eşlemesi eklendi. Güncellemeden önce dünyanızı yedekleyin.

- Normal, delici ve zehirli oklar çarpışma sonrası toplanabilir; patlayıcı ve alevli oklar geri alınamaz.

- Zehirli ok: 10 temel doğrudan hasar ve 10 saniye Zehir I.
- Alevli ok: 10 temel doğrudan hasar ve hedefte 10 saniye yanma; 45 adetlik TaCZ tarifi.
- Alevli ok blok çarpmasında vanilla ateş yerleştirir; yangın yayılması vanilla kurallarına bağlıdır.
- G ile ok seçimi, sadak, HUD ve eldeki/uçan ok modellerine iki yeni tür eklendi.
- TaCZ üretim tarifi: 10 çubuk, 2 demir, 2 altın, 1 örümcek gözü, 1 redstone ve 10 ip; 45 ok üretir.
- Zehirli okta yeşil, alevli okta turuncu uçlar ve şeritler; HUD ve araç çubuğu simgeleri.
- Sadak 9 kullanılabilir yuvaya ve 576 ok kapasitesine çıkarıldı; yalnızca modun özel oklarını kabul eder.
- Geçici atış tanılama kayıtları yayın paketinden kaldırıldı.

## English - 1.0.1

- Fixed launch rendering across viewing directions and synchronization of the initial impact position.
- Shortened arrow shafts by 40% from the tip side while preserving tail placement and tip/vane dimensions.
- Recoverable arrows drop as items when their supporting block is broken, without embedding again.
- Added optional ItemPhysic Guns support for flat ground rendering.
- Lava destroys arrows; only explosive arrows detonate.
- Removed nine custom bow enchantments and their books; enchanting tables and anvils cannot enchant the bow.
- Changed the technical mod ID to `tacticalmilitarybow` with legacy registry remapping. Back up your world before updating.

- Normal, piercing and poison arrows are recoverable on impact; explosive and flame arrows are not.

- Poison arrows: 10 base direct damage and 10 seconds of Poison I.
- Flame arrows: 10 base direct damage and 10 seconds of target burning; 45-count TaCZ recipe.
- Flame arrows place vanilla fire on block impact; fire spread follows vanilla rules.
- Two new arrow types supported by Fire Mode switching, quiver, HUD and held/projectile models.
- TaCZ recipe: 10 sticks, 2 iron ingots, 2 gold ingots, 1 spider eye, 1 redstone and 10 string; produces 45 arrows.
- Green poison and orange flame tips and bands, with matching HUD/inventory icons and EN/TR names.
- Quiver expanded to 9 usable slots and 576 arrows; accepts only this mod's custom arrows.
- Removed temporary launch diagnostic logging from the release package.

# 1.0.0 / Sürüm Notları / Release Notes

## Türkçe

- JEG'den türetilmiş bağımsız makaralı yay; JEG çalışma zamanı bağımlılığı yok.
- Grafit/zeytin yeşili görünüm, yuvarlak gövdeli kırmızı menzil nişangahı.
- Normal, delici ve patlayıcı özel oklar; üçü için 45 adetlik TaCZ tarifleri.
- TaCZ Atış modu değiştirme tuşuyla ok seçimi; mevcut ok iadesi ve olmayan türlerin atlanması.
- Sadak/envanter tüketimi, tür bazında HUD sayacı, ayrı ve görünür ok ikonları.
- Yüksek hızlı okun tam hız vektörü aktarımı; istemcide hız paketinin kesilmesine karşı düzeltme.
- Türkçe ve İngilizce eşya, HUD, tuş, ayar ve büyü metinleri.

## English

- Standalone JEG-derived compound bow; no JEG runtime dependency.
- Graphite/olive appearance and round sight housing with red range markings.
- Normal, piercing and explosive custom arrows, with 45-count TaCZ recipes.
- Arrow selection via TaCZ's Fire Mode key; returns the loaded arrow and skips unavailable types.
- Quiver/inventory consumption, per-type HUD reserve counts and distinct visible arrow icons.
- Full-precision high-speed projectile spawn velocity; prevents client velocity-packet truncation.
- Turkish and English item, HUD, keybinding, settings and enchantment text.
