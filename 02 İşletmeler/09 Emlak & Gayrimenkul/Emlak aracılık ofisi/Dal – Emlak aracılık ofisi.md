---
tip: dal
kod: "09-01"
sektor: "[[09 Emlak & Gayrimenkul]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 09-01 · Emlak aracılık ofisi

> Sektör: [[09 Emlak & Gayrimenkul]] · 1 alt dal · 5 araç

## Özet
- Yetki belgeli işletme, başkasına ait konut, işyeri, arsa veya devre mülke komisyonla aracılık eder.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Emlak aracılık ofisi]] | İTO 68.31.01: 14.828 (İstanbul oda; TR geneli yok) | 10 | Onaylı alt tür |

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
