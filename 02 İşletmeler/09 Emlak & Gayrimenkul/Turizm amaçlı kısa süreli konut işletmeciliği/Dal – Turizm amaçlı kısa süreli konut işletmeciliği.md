---
tip: dal
kod: "09-05"
sektor: "[[09 Emlak & Gayrimenkul]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 12
---
# 09-05 · Turizm amaçlı kısa süreli konut işletmeciliği

> Sektör: [[09 Emlak & Gayrimenkul]] · 1 alt dal · 6 araç

## Özet
- İzin belgeli konutu yüz güne kadar kiraya veren malik işletme veya yüksek nitelikli konutta yönetim işletmesi.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Turizm amaçlı kısa süreli konut işletmeciliği]] | bulunamadı | 12 | Onaylı alt tür |

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
