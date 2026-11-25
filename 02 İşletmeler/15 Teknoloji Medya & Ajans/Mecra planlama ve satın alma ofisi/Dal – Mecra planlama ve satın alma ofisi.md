---
tip: dal
kod: "15-05"
sektor: "[[15 Teknoloji Medya & Ajans]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 40
---
# 15-05 · Mecra planlama ve satın alma ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · 1 alt dal · 40 fonksiyon
> Görsel: [[Ağaç – 15 – Mecra planlama ve satın alma ofisi]]

## Özet
- Mecra planlama ve satın alma ofisi: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Mecra planlama ve satın alma ofisi]] | bulunamadı | 40 | Öncelik 2.4 (C) |

```mermaid
mindmap
  root((Mecra planlama ve satın alma o))
    Mecra planlama ve satın alma ofisi
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
| [[Proje Kapsamı]] | ● | 1/1 |
| [[Bu yazışmayı kapsam maddesine çevir]] | ● | 1/1 |
| [[Kapsam dışı satırları listele]] | ● | 1/1 |
| [[Saat Kullanımı]] | ● | 1/1 |
| [[Bu haftanın faturalanamayan saatini özetle]] | ● | 1/1 |
| [[Müşteri X için faturalanabilir saati göster]] | ● | 1/1 |
| [[Brief Onayı]] | ● | 1/1 |
| [[Brief'ten iş listesi çıkar]] | ● | 1/1 |
| [[Açık revizyon turlarını say]] | ● | 1/1 |
| [[Teslim Takvimi]] | ● | 1/1 |
| [[Bu hafta gecikecek teslimleri listele]] | ● | 1/1 |
| [[Müşteri Y için teslim takvimini özetle]] | ● | 1/1 |
| [[Sözleşme Takibi]] | ● | 1/1 |
| [[30 gün içinde biten retainer'ları göster]] | ● | 1/1 |
| [[Sözleşme yenileme taslağı hazırla]] | ● | 1/1 |
| [[Kaynak Planı]] | ● | 1/1 |
| [[Kim aşırı yüklü?]] | ● | 1/1 |
| [[Sprint için boş kapasiteyi bul]] | ● | 1/1 |
| [[Teklif Paketi]] | ● | 1/1 |
| [[Benzer tekliften taslak üret]] | ● | 1/1 |
| [[Kapsam maddelerini numaralandır]] | ● | 1/1 |
| [[Mecra Planı]] | ● | 1/1 |
| [[Plan ile siparişi karşılaştır]] | ● | 1/1 |
| [[Bu ayın mecra planını özetle]] | ● | 1/1 |
| [[Sipariş Teyidi]] | ● | 1/1 |
| [[Teyidi gelmeyen siparişleri listele]] | ● | 1/1 |
| [[Yayın teyidini eşle]] | ● | 1/1 |
| [[Mecra Faturası]] | ● | 1/1 |
| [[Faturası gelmeyen siparişleri bul]] | ● | 1/1 |
| [[Fatura farklarını listele]] | ● | 1/1 |
| [[Plan Karşılaştırma]] | ● | 1/1 |
| [[Sapma olan mecraları göster]] | ● | 1/1 |
| [[Bütçe aşımını özetle]] | ● | 1/1 |

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
