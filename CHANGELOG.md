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
