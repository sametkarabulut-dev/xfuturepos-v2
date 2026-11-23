---
tip: modul
kod: "10.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Malzeme Takibi

> Kod `10.00.05` · [[10 İnşaat & Yapı]]

## Ne yapar
- İrsaliye kabul ve şantiye sarfiyatı. Çekirdek genişleme: e-Fatura.

## Özellikler
### MVP
- Bugün gelen demiri kaydet
- Beton sarfiyatı metrajı aşıyor mu?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- İrsaliye-metraj sapma ve stok eşiği

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- GİB e-İrsaliye

## Mevzuat
- VUK 509 e-İrsaliye

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
