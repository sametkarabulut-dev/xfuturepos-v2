---
tip: dal
kod: "12-01"
sektor: "[[12 Lojistik & Taşımacılık]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 9
---
# 12-01 · Yurt içi karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · 1 alt dal · 5 araç

## Özet
- Başka firmaların yükünü Türkiye içinde ticari olarak taşıyan filo.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Yurt içi karayolu yük taşımacılığı]] | bulunamadı | 9 | Onaylı alt tür |

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
