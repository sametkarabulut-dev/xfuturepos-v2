---
tip: modul
kod: "15.08.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Destek Kuyruğu

> Kod `15.08.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Ürün destek ticket'ı; proje kabul döngüsü değildir.

## Özellikler
### MVP
- Açık destekleri önceliklendir
- Tekrarlayan hataları grupla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni destek. İşlem: benzer ticket ara. Çıktı: benzer ve öncelik önerisi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
