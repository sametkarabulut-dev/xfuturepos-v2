---
tip: dal
kod: "13-04"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 7
---
# 13-04 · Proje tipi makine ve ekipman imalatı

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 5 araç

## Özet
- Tek teslimi olan makine veya ekipmanı tasarlayıp toplayan 1–50 kişilik imalatçı.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Proje tipi makine ve ekipman imalatı]] | bulunamadı | 7 | Onaylı alt tür |

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
