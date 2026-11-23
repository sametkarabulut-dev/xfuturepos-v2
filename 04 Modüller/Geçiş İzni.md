---
tip: modul
kod: "12.02.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Geçiş İzni

> Kod `12.02.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Ülke geçiş belgesi stok ve kullanım kaydı.

## Özellikler
### MVP
- Romanya geçiş izni kalan adet
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: stok 2 altına düştü. İşlem: uyarı. Çıktı: tedarik notu.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- İkili/çok taraflı geçiş izin rejimleri güzergâha göre değişir.

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
