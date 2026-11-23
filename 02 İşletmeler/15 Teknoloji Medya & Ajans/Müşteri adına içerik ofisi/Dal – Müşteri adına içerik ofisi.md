---
tip: dal
kod: "15-03"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 15-03 · Müşteri adına içerik ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 5 araç

## Özet
- Müşterinin kanalında takvimle yayın yapan retainer ofis. Reklam hesabı asıl işi değildir.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Müşteri adına içerik ofisi]] | bulunamadı | 10 | Onaylı alt tür |

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
