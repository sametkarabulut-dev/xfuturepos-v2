---
tip: dal
kod: "10-04"
sektor: "[[10 İnşaat & Yapı]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 10
---
# 10-04 · Tadilat ve basit onarım

> Sektör: [[10 İnşaat & Yapı]] · 1 alt dal · 5 araç

## Özet
- Taşıyıcıya dokunmayan boya, tesisat tamiri ve iç yenilemeyi doğrudan müşteriye yapan ekip.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Tadilat ve basit onarım]] | bulunamadı | 10 | Onaylı alt tür |

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
