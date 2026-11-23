---
tip: dal
kod: "16-04"
sektor: "[[16 Etkinlik & Organizasyon]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 6
---
# 16-04 · Konser ve küçük festival organizatörlüğü

> Sektör: [[16 Etkinlik & Organizasyon]] · 1 alt dal · 3 araç

## Özet
- Yerel konseri veya küçük festivali üreten organizatör. Stadyum işletmeciliği dışarıdadır.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Konser ve küçük festival organizatörlüğü]] | bulunamadı | 6 | Onaylı alt tür |

## Dalın ortak temeli
- Sektör ortak araçlar + bu altın araçları
- Çekirdek: Muhasebe, e-Fatura, CRM, Personel, Raporlar, AI Asistan, Ayarlar

## Bu daldaki alt dallar (canlı)
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Alt dallar
```
