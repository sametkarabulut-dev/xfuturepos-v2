---
tip: modul
kod: "15.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sipariş Teyidi

> Kod `15.05.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Sipariş ve yayın teyidi eşlemesi.

## Özellikler
### MVP
- Teyidi gelmeyen siparişleri listele
- Yayın teyidini eşle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yayın günü. İşlem: sipariş ile teyidi eşle. Çıktı: eşleşmeyen satırlar.

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
