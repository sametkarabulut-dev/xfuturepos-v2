---
tip: dal
kod: "15-02"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 15-02 · Performans ve reklam hesabı ajansı

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 5 araç

## Özet
- Müşterinin reklam hesabında kampanya süren ofis. Nesne harcama ve erişimdir.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Performans ve reklam hesabı ajansı]] | bulunamadı | 10 | Onaylı alt tür |

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
