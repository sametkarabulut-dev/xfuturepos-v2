---
tip: dal
kod: "13-06"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 7
---
# 13-06 · Üretimi dışarı veren imalatçı

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 5 araç

## Özet
- Kendi modelinin dönüşümünü başka atölyede yaptıran, kendi tezgâhı merkez olmayan imalatçı.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Üretimi dışarı veren imalatçı]] | bulunamadı | 7 | Onaylı alt tür |

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
