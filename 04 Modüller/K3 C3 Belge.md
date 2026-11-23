---
tip: modul
kod: "12.05.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: zorunlu
---
# K3 C3 Belge

> Kod `12.05.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- İşin yurt içi/uluslararası olmasına göre K3 veya C3 yönlendirmesi.

## Özellikler
### MVP
- Bu iş için K3 mü C3 mü gerekir
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: varış ülkesi TR dışı. İşlem: C3 + CMR istisna notu. Çıktı: belge uyarısı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KTY K3/C3 tanımları; U-ETDS yükümlülüğü.

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
