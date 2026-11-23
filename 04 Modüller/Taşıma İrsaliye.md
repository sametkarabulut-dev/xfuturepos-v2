---
tip: modul
kod: "12.01.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Taşıma İrsaliye

> Kod `12.01.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz.

## Özellikler
### MVP
- Sefer 8 için taşıma irsaliyesi taslağı
- Bugün irsaliyesiz kalkan seferler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yükleme onayı. İşlem: taşıma irsaliyesi taslağı. Çıktı: PDF/yazdırma.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Taşımacı: taşıma irsaliyesi. Sevk/e-irsaliye malı gönderen mükellefe (509 VUK); ciro/sektör eşiği taşımacıya otomatik uygulanmaz.

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
