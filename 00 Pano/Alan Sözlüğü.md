---
tip: pano
---
# Alan Sözlüğü

Frontmatter anahtarları ASCII'dir. Türkçe başlıklar `.base` dosyalarında `displayName` ile verilir.

## Ortak alanlar
| Anahtar | Başlık | Değerler |
|---|---|---|
| `tip` | Tip | `sektor` · `dal` · `isletme` · `fonksiyon` · `ihtiyac` · `modul` · `rakip` · `kaynak` |
| `durum` | Durum | `taslak` · `arastiriliyor` · `tamamlandi` · `onay-bekliyor` |

## İşletme türü (`tip: isletme`)
| Anahtar | Başlık | Açıklama |
|---|---|---|
| `sektor` | Sektör | Sektör notuna link |
| `dal` | Dal | Dal notuna link |
| `fonksiyonlar` | Fonksiyonlar | `[[Fonksiyon]]` linkleri |
| `olcek` | Ölçek | `tek-kisilik` · `mikro` · `kucuk-orta` · `zincir` |
| `isletme_sayisi` | İşletme sayısı | Türkiye / oda, kaynaklı metin |
| `isletme_sayisi_n` | Sayı (n) | Parse edilmiş tam sayı (varsa) |
| `sayi_turu` | Sayı türü | `resmi` · `kaynakli` · `tahmin` |
| `nace` | NACE | NACE Rev.2 kodu |
| `pazar_puani` … `aciliyet_puani` | Puanlar | 1–5, 5 = bizim için en iyi |
| `ihtiyaclar` / `moduller` / `rakipler` | Link listeleri | Wiki link |
| `kod` | Kod | Kalıcı ID: sektör-dal-sıra |
| `oneri_harf` | Öneri | ≥3,6 → A · 3,0–3,5 → B · altı → C |
| `oncelik` | Öncelik | Kullanıcı kararı A/B/C |
| `gereksiz` | Gereksiz | `true` → arşive |
| `parca_sart` / `parca_olmali` / `parca_iyi` | Parça sayıları | Şart / Olmalı / İyi olur |
| `parca_durum` | Parça durumu | `tamamlandi` = eşleme bitti |

> Fiyat ve iş modeli önerisi alanları tutulmaz.

**Öncelik (Bases):** `((pazar_puani + odeme_puani + rekabet_puani + kolaylik_puani + aciliyet_puani) / 5).toFixed(1)`

## Ağaç
**Sektör → Dal → Alt dal → Fonksiyon.** Alt dal = işletme türü (`tip: isletme`).

**Parça derecesi:** Şart = olmadan iş yürümez veya yasal zorunluluk · Olmalı = çoğu ister · İyi olur = fark yaratır.

### Dal (`tip: dal`)
| Anahtar | Açıklama |
|---|---|
| `sektor` | Sektör linki |
| `alt_dal_sayisi` | Alt dal sayısı |
| `fonksiyon_sayisi` | Tekil fonksiyon sayısı |

### Fonksiyon / Modül / İhtiyaç / Rakip
Modül: `katman` (cekirdek|sektorel), `arac_turu` (genel|ozel|girmiyoruz), `mvp` (evet|hayir).
İhtiyaç: `kategori` (operasyon|musteri|finans|yasal|pazarlama|personel).
Rakip: `sektorler`, `fiyat`, `guclu`, `zayif`, `web`.
