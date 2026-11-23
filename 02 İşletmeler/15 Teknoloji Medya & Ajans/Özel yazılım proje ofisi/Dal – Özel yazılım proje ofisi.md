---
tip: dal
kod: "15-01"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 15-01 · Özel yazılım proje ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 5 araç

## Özet
- Müşteri sözleşmesiyle yazılım yazan veya mevcut uygulamayı uyarlayan ekip. Kendi ürününü abonelikle yayımlamaz.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Özel yazılım proje ofisi]] | bulunamadı | 10 | Onaylı alt tür |

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
