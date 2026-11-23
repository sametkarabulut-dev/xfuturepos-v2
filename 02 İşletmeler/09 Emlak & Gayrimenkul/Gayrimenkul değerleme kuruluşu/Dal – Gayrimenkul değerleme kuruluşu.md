---
tip: dal
kod: "09-04"
sektor: "[[09 Emlak & Gayrimenkul]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 09-04 · Gayrimenkul değerleme kuruluşu

> Sektör: [[09 Emlak & Gayrimenkul]] · 1 alt dal · 5 araç

## Özet
- SPK III-62.3 listesindeki anonim şirket rapor üretir; banka raporu için ayrıca BDDK listesi gerekir.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Gayrimenkul değerleme kuruluşu]] | İTO 68.32.01: 1.174 | 10 | Onaylı alt tür |

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
