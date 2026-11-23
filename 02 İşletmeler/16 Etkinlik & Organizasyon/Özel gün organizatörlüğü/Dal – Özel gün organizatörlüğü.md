---
tip: dal
kod: "16-02"
sektor: "[[16 Etkinlik & Organizasyon]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 6
---
# 16-02 · Özel gün organizatörlüğü

> Sektör: [[16 Etkinlik & Organizasyon]] · 1 alt dal · 3 araç

## Özet
- Çift veya aile adına günü planlayan, salonu işletmeyen firma.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Özel gün organizatörlüğü]] | bulunamadı | 6 | Onaylı alt tür |

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
