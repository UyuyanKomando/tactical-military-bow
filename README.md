# [TaCZ] Tactical Military Bow

## Türkçe

Minecraft 1.20.1 Forge için TaCZ ve LesRaisins üretim sistemiyle çalışan bağımsız makaralı yay. JEG'nin yayından türetilmiştir; JEG'nin kurulu olması gerekmez. Normal, delici, patlayıcı, zehirli ve alevli oklar; kemere takılan sadak; ok seçimi ve mühimmat HUD'u içerir.

### Kurulum ve bağımlılıklar

Java 17, Minecraft 1.20.1 ve Forge 47.x kullanın. Test edilen Forge sürümü: 47.4.10. Aşağıdaki modları ve bu modun JAR dosyasını `mods` klasörüne koyun. Sunucuda ve istemcide aynı sürümleri kullanın.

| Mod | Kabul edilen sürüm | Test edilen sürüm |
| --- | --- | --- |
| [TaCZ] Timeless and Classics Zero Guns | 1.1.8 ve üzeri, 1.2'den düşük | 1.1.8-hotfix2 |
| [TACZ] LesRaisins Tactical Equipements | 0.4.3 ve üzeri, 0.5'ten düşük | 0.4.3 |
| Curios API | 5.14.1 ve üzeri, 6'dan düşük | 5.14.1 |
| GeckoLib | 4.8.4 ve üzeri, 5'ten düşük | 4.8.4 |

Güncelleme yaparken modun eski JAR dosyasını kaldırın ve dünyanızı yedekleyin.

### Kullanım

Sol tıkla kirişi çekip bırakarak ateş edin; sağ tıkla nişan alın. R doldurur, O etkileşim içindir. Yay elindeyken TaCZ'nin Atış modu değiştirme tuşu (varsayılan G) ok türünü değiştirir; tuş yeniden atanabilir. Çekiş ve doldurma sırasında ok değiştirilemez. Önceki ok iade edilir; mevcut olmayan türler atlanır. HUD yay adını, yay simgesini, ok türünü ve o türün yedek adedini gösterir.

Sadağı Curios kemer yuvasına takın. Sadağı elinizde tutarken sağ tık menüsünü açar; Shift + sağ tık sıradaki dolu yuvayı seçer. Sadak dokuz yığın, toplam 576 ok tutar. Sadak yalnızca modun beş özel okunu kabul eder; diğer eşyalar ve Minecraft'ın standart okları eklenemez.

### Oklar ve tarifler

Normal, delici ve zehirli oklar çarptıkları yerde saplı kalır; yanına gidince yeniden toplanabilir. Saplandığı blok kırılınca ok eşya olarak yere düşer ve tekrar saplanmaz. Saplı oklar beş dakika sonra kaybolur. Patlayıcı ve alevli oklar etkilerini uyguladıktan sonra kaybolur ve geri alınamaz. Creative ve IgnoreAmmo atışları geri alınabilir ok üretmez.

Yay büyülenemez; bu moda özel büyüler ve büyü kitapları kaldırılmıştır. Ok gövdeleri uç tarafından %40 kısaltılmıştır. ItemPhysic Guns kuruluysa yere atılan yay ve oklar yatay durur; bu uyumluluk isteğe bağlıdır.

Beş ok türü de TaCZ mühimmat montaj masasının **Explosives & Projectiles** bölümünde üretilir. Her tarif **45 ok** verir.

| Ok | Malzeme | Temel doğrudan hasar |
| --- | --- | --- |
| Normal | 10 çubuk + 2 demir külçesi + 10 ip | 20 |
| Delici | 10 çubuk + 2 demir külçesi + 2 altın külçesi + 10 ip | 35 |
| Patlayıcı | 10 çubuk + 2 demir külçesi + 2 altın külçesi + 10 barut + 10 ip | 20 + alan patlaması |
| Zehirli | 10 çubuk + 2 demir külçesi + 2 altın külçesi + 1 örümcek gözü + 1 redstone + 10 ip | 10 + 10 saniye Zehir I |
| Alevli | 10 çubuk + 2 demir külçesi + 2 altın külçesi + 1 çakmak taşı + 1 redstone + 10 ip | 10 + 10 saniye yanma |

Alevli ok başarılı vuruşta hedefi 10 saniye yakar ve blok çarpmasında uygun bitişik boşluğa vanilla ateş yerleştirir. Yangının yayılması ve ahşabı tüketmesi vanilla yanıcılık kurallarını ve `doFireTick` ayarını izler; Nether ahşapları yanmaz. Su, yağmur, ateşe bağışıklık ve koruma kuralları geçerlidir.

Zehirli okun tam çekişte temel hasarı 10'dur; kafa vuruşu çarpanı uygulanır. Zehir, başarılı vuruşta uygulanır; zehre bağışık canlılar etkilenmez.

Tam çekişte kafa vuruşu çarpanı %150'dir; normal ok 30, delici ok 52,5 temel kafa hasarı verir. Zırh, büyüler ve sunucu ayarları nihai hasarı etkiler. Delici ok 1,75 kat doğrudan hasar verir; ek zırh delme sağlamaz. Normal ve delici ok mevcut cam/ince blok kırma kurallarını korur.

Patlayıcı ok TaCZ M320 profilini kullanır: 50 patlama hasarı, 6 blok yarıçap, geri itme açık, patlamayla blok kırma kapalı. Çarpmada veya havada 30 saniye sonunda patlar. Yakındaki oyuncular ve atıcı da zarar görebilir. Lava değen oklar yok olur; yalnızca patlayıcı ok patlar.

### Lisans ve katkılar

Geliştirici: **Korkuluk**. Yay, **Just Enough Guns (JEG)** yayından türetilmiştir; orijinal yay tasarımı **MigaMi**'ye aittir. Diğer kaynak katkıları: **MrCrayfish, Bomb787 ve NineZero**. Ok ve sadak modelleri bu proje için üretilmiştir.

GPLv3 lisans metni ve ilgili üçüncü taraf bildirimleri pakete dahildir. Ayrıntılar için `LICENSE-GPL-3.0.txt` ve `THIRD-PARTY-NOTICES.md` dosyalarına bakın. JEG kurulumu gerekmez.

## English

A standalone compound bow for Minecraft 1.20.1 Forge, integrated with TaCZ and LesRaisins crafting. Derived from the JEG bow; JEG itself is not required. Includes normal, piercing, explosive, poison and flame arrows, a belt quiver, arrow selection and an ammo HUD.

### Installation and dependencies

Use Java 17, Minecraft 1.20.1 and Forge 47.x. Tested Forge version: 47.4.10. Install the following dependencies and this mod's JAR in `mods`. Use matching versions on client and server.

| Mod | Accepted version | Tested version |
| --- | --- | --- |
| [TaCZ] Timeless and Classics Zero Guns | 1.1.8 or newer, below 1.2 | 1.1.8-hotfix2 |
| [TACZ] LesRaisins Tactical Equipements | 0.4.3 or newer, below 0.5 | 0.4.3 |
| Curios API | 5.14.1 or newer, below 6 | 5.14.1 |
| GeckoLib | 4.8.4 or newer, below 5 | 4.8.4 |

When updating, remove the mod's previous JAR and back up your world.

### Controls

Hold and release left click to draw and fire; right click to aim. R reloads; O interacts. While holding the bow, TaCZ's Fire Mode key (G by default, rebindable) cycles arrow types. Switching is blocked while drawing or reloading. The old loaded arrow is returned and unavailable types are skipped. The HUD shows the bow name/icon, arrow type and that type's reserve count.

Equip the quiver in the Curios belt slot. Right click while holding it opens the menu; Shift + right click selects the next occupied slot. It holds nine stacks, up to 576 arrows. The quiver accepts only this mod's five custom arrows, not other items or vanilla Minecraft arrows.

### Arrows and recipes

Normal, piercing and poison arrows remain embedded on impact and can be recovered by approaching them. Breaking the supporting block drops the arrow as an item instead of making it embed again. Embedded arrows despawn after five minutes. Explosive and flame arrows disappear after their effects and cannot be recovered. Creative and IgnoreAmmo shots do not create recoverable arrows.

The bow cannot be enchanted; this mod's custom enchantments and enchanted books have been removed. Arrow shafts are 40% shorter from the tip side. With ItemPhysic Guns installed, dropped bows and arrows lie flat; this integration is optional.

All five arrow types are crafted in the TaCZ ammo workbench's **Explosives & Projectiles** section. Each recipe produces **45 arrows**.

| Arrow | Materials | Base direct damage |
| --- | --- | --- |
| Normal | 10 sticks + 2 iron ingots + 10 string | 20 |
| Piercing | 10 sticks + 2 iron ingots + 2 gold ingots + 10 string | 35 |
| Explosive | 10 sticks + 2 iron ingots + 2 gold ingots + 10 gunpowder + 10 string | 20 + area explosion |
| Poison | 10 sticks + 2 iron ingots + 2 gold ingots + 1 spider eye + 1 redstone + 10 string | 10 + 10 seconds of Poison I |
| Flame | 10 sticks + 2 iron ingots + 2 gold ingots + 1 flint + 1 redstone + 10 string | 10 + 10 seconds of burning |

Flame arrows ignite targets for 10 seconds on successful damage and place vanilla fire in a valid adjacent empty block on block impact. Fire spread and wood consumption follow vanilla flammability rules and `doFireTick`; Nether wood does not burn. Water, rain, fire immunity and protection rules apply.

Poison arrows deal 10 base damage at full charge, with the headshot multiplier applied. Poison applies on successful damage; poison-immune mobs are unaffected.

Full-charge headshot multiplier: 150%, giving 30 normal or 52.5 piercing base headshot damage. Armor, enchantments and server settings affect final damage. Piercing arrows apply a 1.75x direct-damage multiplier, not additional armor bypass. Normal and piercing arrows retain the existing glass/fragile-block impact rules.

Explosive arrows use the TaCZ M320 profile: 50 explosion damage, radius 6, knockback enabled and explosion block destruction disabled. They detonate on impact or after 30 seconds airborne. Nearby players, including the shooter, can be hurt. Arrows touching lava are destroyed; only explosive arrows detonate.

### License and credits

Developed by **Korkuluk**. The bow is derived from **Just Enough Guns (JEG)**; original bow by **MigaMi**. Additional upstream credits: **MrCrayfish, Bomb787 and NineZero**. Arrow and quiver models were created for this project.

The GPLv3 license text and applicable third-party notices are included in the package. See `LICENSE-GPL-3.0.txt` and `THIRD-PARTY-NOTICES.md` for details. JEG itself is not required.
