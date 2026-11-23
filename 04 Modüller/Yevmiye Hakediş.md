---
tip: modul
kod: "10.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yevmiye Hakediş

> Kod `10.02.02` · [[10 İnşaat & Yapı]]

## Ne yapar
- Taşeron hakediş paketi.

## Özellikler
### MVP
- Bu ay hakedişimi hazırla
- Kesinti sonrası neti hesapla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Dönem paketi + eksik tutanak

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura

## Mevzuat
- Sözleşme kesintileri

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
