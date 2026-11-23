---
tip: dal
kod: "10-07"
sektor: "[[10 İnşaat & Yapı]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 10-07 · Yapı denetim kuruluşu

> Sektör: [[10 İnşaat & Yapı]] · 1 alt dal · 5 araç

## Özet
- 4708 kapsamında yalnızca denetim yapan, tutanak ve seviye tespiti yürüten kuruluş.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Yapı denetim kuruluşu]] | bulunamadı | 10 | Onaylı alt tür |

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
