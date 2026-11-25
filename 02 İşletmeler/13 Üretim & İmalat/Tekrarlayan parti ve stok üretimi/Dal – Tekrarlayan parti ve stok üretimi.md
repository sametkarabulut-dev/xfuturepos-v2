---
tip: dal
kod: "13-05"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 35
---
# 13-05 · Tekrarlayan parti ve stok üretimi

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 35 fonksiyon
> Görsel: [[Ağaç – 13 – Tekrarlayan parti ve stok üretimi]]

## Özet
- Tekrarlayan parti ve stok üretimi: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Tekrarlayan parti ve stok üretimi]] | bulunamadı | 35 | Öncelik 3.4 (B) |

```mermaid
mindmap
  root((Tekrarlayan parti ve stok üret))
    Tekrarlayan parti ve stok üretimi
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
| [[Parti Plan]] | ● | 1/1 |
| [[SKU-A için 500'lük parti aç]] | ● | 1/1 |
| [[Bu ay planı]] | ● | 1/1 |
| [[Lot Barkod]] | ● | 1/1 |
| [[Lot L-2411 oluştur]] | ● | 1/1 |
| [[Lot L-2411 nereye gitti]] | ● | 1/1 |
| [[Min Max]] | ● | 1/1 |
| [[Min altına düşenleri listele]] | ● | 1/1 |
| [[Min 200 yap]] | ● | 1/1 |
| [[Verim Rapor]] | ● | 1/1 |
| [[SKU-B verim raporu]] | ● | 1/1 |
| [[Alternatif Reçete]] | ● | 1/1 |
| [[Alternatif reçeteyi uygula]] | ● | 1/1 |

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
