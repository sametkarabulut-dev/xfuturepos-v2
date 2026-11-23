---
tip: modul
kod: "10.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sevkiyat İrsaliye

> Kod `10.05.02` · [[10 İnşaat & Yapı]]

## Ne yapar
- Sevk + e-İrsaliye. Çekirdek genişleme: e-Fatura.

## Özellikler
### MVP
- Yarınki sevkiyatları listele
- e-İrsaliye kes
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sevk öncesi belge kontrolü

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- GİB e-İrsaliye

## Mevzuat
- VUK 509

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
