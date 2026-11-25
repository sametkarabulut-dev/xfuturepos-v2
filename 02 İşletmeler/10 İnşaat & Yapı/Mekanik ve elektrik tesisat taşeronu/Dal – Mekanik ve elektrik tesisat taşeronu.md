---
tip: dal
kod: "10-03"
sektor: "[[10 İnşaat & Yapı]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 43
---
# 10-03 · Mekanik ve elektrik tesisat taşeronu

> Sektör: [[10 İnşaat & Yapı]] · 1 alt dal · 43 fonksiyon
> Görsel: [[Ağaç – 10 – Mekanik ve elektrik tesisat taşeronu]]

## Özet
- Mekanik ve elektrik tesisat taşeronu: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Mekanik ve elektrik tesisat taşeronu]] | bulunamadı | 43 | Öncelik 3.2 (B) |

```mermaid
mindmap
  root((Mekanik ve elektrik tesisat ta))
    Mekanik ve elektrik tesisat taşeronu
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
| [[Proje Kartı]] | ● | 1/1 |
| [[Aktif şantiyeleri listele]] | ● | 1/1 |
| [[C blok projesini askıya al]] | ● | 1/1 |
| [[Saha Puantajı]] | ● | 1/1 |
| [[Bugün B blokta kaç kişi var?]] | ● | 1/1 |
| [[Elektrik ekibi puantajını özetle]] | ● | 1/1 |
| [[Metraj Hakediş]] | ● | 1/1 |
| [[Mart hakediş taslağını hazırla]] | ● | 1/1 |
| [[Kalıp m² farkını göster]] | ● | 1/1 |
| [[Şantiye Günlüğü]] | ● | 1/1 |
| [[Bugünkü günlük raporu hazırla]] | ● | 1/1 |
| [[Son 7 gün çalışılmayan günleri göster]] | ● | 1/1 |
| [[Malzeme Takibi]] | ● | 1/1 |
| [[Bugün gelen demiri kaydet]] | ● | 1/1 |
| [[Beton sarfiyatı metrajı aşıyor mu?]] | ● | 1/1 |
| [[İSG Kontrol]] | ● | 1/1 |
| [[Süresi dolan İSG belgelerini listele]] | ● | 1/1 |
| [[Ramak kala aç]] | ● | 1/1 |
| [[Taşeron Sözleşme]] | ● | 1/1 |
| [[Yeni sıva taşeron sözleşmesi oluştur]] | ● | 1/1 |
| [[Ek iş protokollerini göster]] | ● | 1/1 |
| [[Keşif Metraj]] | ● | 1/1 |
| [[Kollektör hattı metrajını güncelle]] | ● | 1/1 |
| [[Elektrik poz farkını göster]] | ● | 1/1 |
| [[Test Devreye]] | ● | 1/1 |
| [[Isıtma basınç testini kaydet]] | ● | 1/1 |
| [[Açık testleri listele]] | ● | 1/1 |
| [[Malzeme Poz]] | ● | 1/1 |
| [[Yangın pompalarını teslim al]] | ● | 1/1 |
| [[Eksik vana listesi]] | ● | 1/1 |
| [[As-Built Proje]] | ● | 1/1 |
| [[As-built’i müellife gönder]] | ● | 1/1 |
| [[Bekleyen as-built’ler]] | ● | 1/1 |

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
