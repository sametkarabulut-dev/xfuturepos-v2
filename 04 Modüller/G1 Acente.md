---
tip: modul
kod: "12.03.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# G1 Acente

> Kod `12.03.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Başka N belgesi adına yük kabul eden G1 acente sözleşmeleri.

## Özellikler
### MVP
- G1 sözleşmeli ambarları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sözleşme bitişine 30 gün. İşlem: yenileme uyarısı. Çıktı: yönetici kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- G1 acentelik ≠ N işletmeciliği.

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
