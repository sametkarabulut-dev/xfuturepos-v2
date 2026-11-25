---
tip: dal
kod: "10-02"
sektor: "[[10 İnşaat & Yapı]]"
durum: tamamlandi
alt_dal_sayisi: 1
fonksiyon_sayisi: 43
---
# 10-02 · Küçük ölçekli bina müteahhidi

> Sektör: [[10 İnşaat & Yapı]] · 1 alt dal · 43 fonksiyon
> Görsel: [[Ağaç – 10 – Küçük ölçekli bina müteahhidi]]

## Özet
- Küçük ölçekli bina müteahhidi: onaylı alt işletme tür(ler)i ve bağlanan araç/fonksiyonlar.

## Alt dallar
| # | Alt dal | İşletme sayısı | Fonksiyon | Not |
|---|---|---|---|---|
| A1 | [[Küçük ölçekli bina müteahhidi]] | KOSGEB inşaat KOBİ kümesi içinde; alt kırılım bulunamadı | 43 | Öncelik 3.8 (A) |

```mermaid
mindmap
  root((Küçük ölçekli bina müteahhidi))
    Küçük ölçekli bina müteahhidi
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
| [[Ruhsat Takibi]] | ● | 1/1 |
| [[Ruhsat bekleyen projeleri göster]] | ● | 1/1 |
| [[İskan evrak listesini çıkar]] | ● | 1/1 |
| [[İş Programı]] | ● | 1/1 |
| [[Kaba inşaat bitişini kaydır]] | ● | 1/1 |
| [[Kritik gecikmeleri özetle]] | ● | 1/1 |
| [[Maliyet Bütçe]] | ● | 1/1 |
| [[Bu ay bütçe sapmasını göster]] | ● | 1/1 |
| [[Demir kalemini artır]] | ● | 1/1 |
| [[Şef Atama]] | ● | 1/1 |
| [[Bu işe şef ata]] | ● | 1/1 |
| [[Şefin aktif m² toplamını göster]] | ● | 1/1 |

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
