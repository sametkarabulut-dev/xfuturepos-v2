---
tip: dal
kod: "12-07"
sektor: "[[12 Lojistik & Taşımacılık]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 12-07 · Depolama ve sipariş karşılama

> Sektör: [[12 Lojistik & Taşımacılık]] · 1 alt dal · 5 araç

## Özet
- Başkasının malını kabul eden, sipariş olunca toplayıp taşıyıcıya teslim eden depo.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Depolama ve sipariş karşılama]] | bulunamadı | 8 | Onaylı alt tür |

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
