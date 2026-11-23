---
tip: modul
kod: "13.04.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Milestone Ödeme

> Kod `13.04.03` · [[13 Üretim & İmalat]]

## Ne yapar
- Proje hakediş basamakları. Çekirdek genişleme: Muhasebe & Gelir-Gider.

## Özellikler
### MVP
- P-12 yüzde 40 faturasını hazırla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Aşama onayında fatura taslağı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura, Muhasebe

## Mevzuat
- Yok / panel kaydı

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
