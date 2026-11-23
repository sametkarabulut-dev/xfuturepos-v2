---
tip: dal
kod: "12-02"
sektor: "[[12 Lojistik & Taşımacılık]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 8
---
# 12-02 · Uluslararası karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · 1 alt dal · 5 araç

## Özet
- Sınır geçen ticari karayolu seferi; belge bugün çoğunlukla L2’dir.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Uluslararası karayolu yük taşımacılığı]] | bulunamadı | 8 | Onaylı alt tür |

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
