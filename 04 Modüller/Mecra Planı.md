---
tip: modul
kod: "15.05.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Mecra Planı

> Kod `15.05.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Mecra, tarih ve bütçe kalemi planı.

## Özellikler
### MVP
- Plan ile siparişi karşılaştır
- Bu ayın mecra planını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: plan kaydı. İşlem: kalemleri doğrula. Çıktı: eksik plan kalemi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Ticari Reklam Yönetmeliği: reklam ajansı / yayına aracılık.

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
