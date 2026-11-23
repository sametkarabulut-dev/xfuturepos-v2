---
tip: dal
kod: "15-05"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 15-05 · Mecra planlama ve satın alma ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 4 araç

## Özet
- Müşteri bütçesini mecralara yerleştiren küçük ofis. Günü Ads Manager içinde geçmez.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Mecra planlama ve satın alma ofisi]] | bulunamadı | 8 | Onaylı alt tür |

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
