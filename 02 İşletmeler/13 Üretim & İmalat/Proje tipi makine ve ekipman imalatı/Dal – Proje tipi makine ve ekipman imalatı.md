---
tip: dal
kod: "13-03"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 34
---
# 13-03 · Proje tipi makine ve ekipman imalatı

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 34 fonksiyon
> Görsel: [[Ağaç – 13 – Proje tipi makine ve ekipman imalatı]]

## Özet
- Proje tipi makine ve ekipman imalatı: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Proje tipi makine ve ekipman imalatı]] | bulunamadı | 34 | Öncelik 2.6 (C) |

```mermaid
mindmap
  root((Proje tipi makine ve ekipman i))
    Proje tipi makine ve ekipman imalatı
```

## Dalın ortak temeli
- Çekirdek: [[Muhasebe ve Gelir-Gider]], [[e-Fatura ve e-Arşiv]], [[CRM]], [[Personel ve Vardiya]], [[Raporlar]], [[AI Asistan]], [[Ayarlar]]
- Sektör ortak araçlar + bu dalın alt tür araçları

## Fonksiyon matrisi
> ● = kullanıyor.

| Fonksiyon | A1 | Kullanım |
|---|---|---|
| [[Muhasebe ve Gelir-Gider]] | ● | 1/1 |
| [[e-Fatura ve e-Arşiv]] | ● | 1/1 |
| [[CRM]] | ● | 1/1 |
| [[Personel ve Vardiya]] | ● | 1/1 |
| [[Raporlar]] | ● | 1/1 |
| [[AI Asistan]] | ● | 1/1 |
| [[Ayarlar]] | ● | 1/1 |
| [[İş Emri (Üretim)]] | ● | 1/1 |
| [[Sipariş 452 için iş emri aç]] | ● | 1/1 |
| [[Geciken iş emirlerini listele]] | ● | 1/1 |
| [[Reçete BOM]] | ● | 1/1 |
| [[Gömlek reçetesini göster]] | ● | 1/1 |
| [[Fire oranını yüzde 5 yap]] | ● | 1/1 |
| [[Fire Kayıt]] | ● | 1/1 |
| [[İş emri 88 fire kaydet 12 adet]] | ● | 1/1 |
| [[Bu hafta fire aşımı]] | ● | 1/1 |
| [[Depo Sevk]] | ● | 1/1 |
| [[İş emri 90 için sac çıkar]] | ● | 1/1 |
| [[Fasoncuda kalan bakiyeyi göster]] | ● | 1/1 |
| [[Fason Mutabakat]] | ● | 1/1 |
| [[ABC Fason mutabakatını çıkar]] | ● | 1/1 |
| [[Fire aşımını hakedişten kes]] | ● | 1/1 |
| [[Proje BOM]] | ● | 1/1 |
| [[Proje P-12 BOM v3]] | ● | 1/1 |
| [[Revizyon farkını göster]] | ● | 1/1 |
| [[Montaj Aşama]] | ● | 1/1 |
| [[P-12 hangi aşamada]] | ● | 1/1 |
| [[Test aşamasına geç]] | ● | 1/1 |
| [[Milestone Ödeme]] | ● | 1/1 |
| [[P-12 yüzde 40 faturasını hazırla]] | ● | 1/1 |
| [[Teknik Revizyon]] | ● | 1/1 |
| [[Revizyon R2 ekle]] | ● | 1/1 |
| [[Saha Sevk]] | ● | 1/1 |
| [[Sevkiyat checklist]] | ● | 1/1 |

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
