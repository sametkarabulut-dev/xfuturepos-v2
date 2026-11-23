---
tip: modul
kod: "10.03.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Malzeme Poz

> Kod `10.03.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Tesisat malzeme-poz eşlemesi.

## Özellikler
### MVP
- Yangın pompalarını teslim al
- Eksik vana listesi
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- İrsaliye-poz uyumsuzluk uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-İrsaliye

## Mevzuat
- VUK 509

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
