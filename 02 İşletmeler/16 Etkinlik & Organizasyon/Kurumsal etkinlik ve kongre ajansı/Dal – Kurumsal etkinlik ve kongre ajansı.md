---
tip: dal
kod: "16-03"
sektor: "[[16 Etkinlik & Organizasyon]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 5
---
# 16-03 · Kurumsal etkinlik ve kongre ajansı

> Sektör: [[16 Etkinlik & Organizasyon]] · 1 alt dal · 3 araç

## Özet
- Şirket veya kurum adına lansman, kongre, gala ve fuar katılımını proje olarak yürüten ajans.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Kurumsal etkinlik ve kongre ajansı]] | bulunamadı | 5 | Onaylı alt tür |

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
