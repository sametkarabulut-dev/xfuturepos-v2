---
tip: dal
kod: "12-04"
sektor: "[[12 Lojistik & Taşımacılık]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 12-04 · Şehir içi kurye ve dağıtım

> Sektör: [[12 Lojistik & Taşımacılık]] · 1 alt dal · 5 araç

## Özet
- İl içi veya komşu ilçelerde tasnif olmadan taşınan kurye gönderisi.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Şehir içi kurye ve dağıtım]] | bulunamadı | 8 | Onaylı alt tür |

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
