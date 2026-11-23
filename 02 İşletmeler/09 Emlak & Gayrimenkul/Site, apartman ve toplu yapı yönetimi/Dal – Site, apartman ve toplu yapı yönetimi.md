---
tip: dal
kod: "09-03"
sektor: "[[09 Emlak & Gayrimenkul]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 09-03 · Site, apartman ve toplu yapı yönetimi

> Sektör: [[09 Emlak & Gayrimenkul]] · 1 alt dal · 5 araç

## Özet
- Profesyonel yönetici, kat mülkiyetli yapının ortak giderini, personelini ve kurullarını yürütür.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Site, apartman ve toplu yapı yönetimi]] | İTO 68.32.02: 795 (ücretli yönetim; site yönetim TR geneli bulunamadı) | 10 | Onaylı alt tür |

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
