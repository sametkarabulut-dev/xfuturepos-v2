---
tip: dal
kod: "15-06"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 15-06 · Kendi mecrasını işleten yayıncı

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 4 araç

## Özet
- Kendi yayın takvimini yürüten ve kendi alan veya zamanını satan küçük dijital yayın.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Kendi mecrasını işleten yayıncı]] | bulunamadı | 8 | Onaylı alt tür |

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
