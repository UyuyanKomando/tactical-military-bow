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
