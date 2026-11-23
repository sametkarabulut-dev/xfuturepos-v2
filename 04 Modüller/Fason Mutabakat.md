---
tip: modul
kod: "13.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Fason Mutabakat

> Kod `13.00.05` · [[13 Üretim & İmalat]]

## Ne yapar
- Sevk, dönüş, kalite, fire, hakediş ve fatura eşleştirme zinciri. Çekirdek genişleme: Muhasebe & Gelir-Gider.

## Özellikler
### MVP
- ABC Fason mutabakatını çıkar
- Fire aşımını hakedişten kes
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Dönem sonu hakediş taslağı; fatura farkını satır satır listeler

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura, Mikro cari

## Mevzuat
- Fason sevk belge/mülkiyet ayrımı mali müşavir yönlendirmesiyle

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
