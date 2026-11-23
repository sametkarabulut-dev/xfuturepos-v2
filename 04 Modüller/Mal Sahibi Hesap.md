---
tip: modul
kod: "12.07.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Mal Sahibi Hesap

> Kod `12.07.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Depolama ve işlem ücretleri; dönem mutabakatı çekirdek e-Faturaya el verir.

## Özellikler
### MVP
- Mart mutabakatını hazırla
- Faturalanacak bekleyen işlemler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: ay sonu. İşlem: işlem dökümü. Çıktı: onaylı mutabakat taslağı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
