---
tip: dal
kod: "13-02"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 35
---
# 13-02 · Gıda işleme

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 35 fonksiyon
> Görsel: [[Ağaç – 13 – Gıda işleme]]

## Özet
- Gıda işleme: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Gıda işleme]] | bulunamadı | 35 | Öncelik 2.8 (C) |

```mermaid
mindmap
  root((Gıda işleme))
    Gıda işleme
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
| [[Lot İzle]] | ● | 1/1 |
| [[Lot G-90 nereye gitti]] | ● | 1/1 |
| [[Bu satışın hammaddesi]] | ● | 1/1 |
| [[SKT Parti]] | ● | 1/1 |
| [[SKT'si 7 gün kalanlar]] | ● | 1/1 |
| [[FEFO ile sevk]] | ● | 1/1 |
| [[Kayıt Onay]] | ● | 1/1 |
| [[Kayıt belgesi bitiş tarihi]] | ● | 1/1 |
| [[Onay kapsamım ne]] | ● | 1/1 |
| [[Soğuk Kayıt]] | ● | 1/1 |
| [[Soğuk oda bugün kaydı]] | ● | 1/1 |
| [[Geri Çağır]] | ● | 1/1 |
| [[Lot G-90 geri çağır]] | ● | 1/1 |

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
