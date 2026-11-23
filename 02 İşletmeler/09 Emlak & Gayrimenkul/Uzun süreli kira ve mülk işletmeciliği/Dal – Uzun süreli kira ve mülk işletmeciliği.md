---
tip: dal
kod: "09-02"
sektor: "[[09 Emlak & Gayrimenkul]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 09-02 · Uzun süreli kira ve mülk işletmeciliği

> Sektör: [[09 Emlak & Gayrimenkul]] · 1 alt dal · 5 araç

## Özet
- Kendi veya sözleşmeyle başkasının taşınmazını uzun süreli kiracı ilişkisiyle işler.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Uzun süreli kira ve mülk işletmeciliği]] | İTO 68.20.02: 5.013 (kendi taşınmazını kiralama kümesi) | 10 | Onaylı alt tür |

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
