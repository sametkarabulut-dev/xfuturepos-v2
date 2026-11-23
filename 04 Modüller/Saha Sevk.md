---
tip: modul
kod: "13.04.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Saha Sevk

> Kod `13.04.05` · [[13 Üretim & İmalat]]

## Ne yapar
- Makine sevkiyat checklist

## Özellikler
### MVP
- Sevkiyat checklist
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik kalemde sevki bloklar

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro e-İrsaliye API

## Mevzuat
- GTİP 72/73 kapsamı kontrol edilmeli Doğrulama kapanışı: Mikro e-İrsaliye uçları açıldı. Saha sevki taslaktır, gönderim onayla.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

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
