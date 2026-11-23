---
tip: dal
kod: "13-01"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 13-01 · Siparişe göre kısa çevrim atölye

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 5 araç

## Özet
- Müşterinin ölçüsüne göre saatler veya birkaç gün süren ayrı iş çıkaran atölye.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Siparişe göre kısa çevrim atölye]] | bulunamadı | 8 | Onaylı alt tür |

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
