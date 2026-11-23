---
tip: dal
kod: "16-01"
sektor: "[[16 Etkinlik & Organizasyon]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 6
---
# 16-01 · Düğün, balo ve davet mekânı işletmeciliği

> Sektör: [[16 Etkinlik & Organizasyon]] · 1 alt dal · 3 araç

## Özet
- Tarihi ve salonu satan işletme. Mekânsız planlayıcı bu satırda değildir.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Düğün, balo ve davet mekânı işletmeciliği]] | bulunamadı | 6 | Onaylı alt tür |

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
