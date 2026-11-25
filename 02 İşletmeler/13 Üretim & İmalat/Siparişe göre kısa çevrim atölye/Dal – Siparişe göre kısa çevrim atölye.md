---
tip: dal
kod: "13-04"
sektor: "[[13 Üretim & İmalat]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 35
---
# 13-04 · Siparişe göre kısa çevrim atölye

> Sektör: [[13 Üretim & İmalat]] · 1 alt dal · 35 fonksiyon
> Görsel: [[Ağaç – 13 – Siparişe göre kısa çevrim atölye]]

## Özet
- Siparişe göre kısa çevrim atölye: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Siparişe göre kısa çevrim atölye]] | bulunamadı | 35 | Öncelik 4.0 (A) |

```mermaid
mindmap
  root((Siparişe göre kısa çevrim atöl))
    Siparişe göre kısa çevrim atölye
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
| [[Sipariş Emri]] | ● | 1/1 |
| [[Sipariş 120'yi iş emrine çevir]] | ● | 1/1 |
| [[Bugün teslimler]] | ● | 1/1 |
| [[Atölye Kuyruk]] | ● | 1/1 |
| [[Torna kuyruğunu sırala]] | ● | 1/1 |
| [[Acil işi öne al]] | ● | 1/1 |
| [[Termin Alarm]] | ● | 1/1 |
| [[Geç kalacak işleri söyle]] | ● | 1/1 |
| [[Müşteri X gecikmeleri]] | ● | 1/1 |
| [[Tezgah Yük]] | ● | 1/1 |
| [[Bu hafta freze doluluk]] | ● | 1/1 |
| [[Revize Sipariş]] | ● | 1/1 |
| [[Sipariş 55 miktarı 80 yap]] | ● | 1/1 |

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
