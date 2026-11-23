---
tip: modul
kod: "15.04.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Arşiv Dolabı

> Kod `15.04.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Teslim arşivi ve lisanslı stok ayrımı.

## Özellikler
### MVP
- Lisansı belirsiz stokları bul
- Proje arşivini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: proje kapanışı. İşlem: arşiv eksiklerini tara. Çıktı: eksik arşiv listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Reklam filmi veya görsel üretiliyorsa Ticari Reklam Yönetmeliği.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

## Kullanan işletme türleri
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan işletme türleri
```
