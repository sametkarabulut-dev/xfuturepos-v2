---
tip: modul
kod: "12.02.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# CMR Belgesi

> Kod `12.02.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı.

## Özellikler
### MVP
- TR DE seferi için CMR taslağı
- CMR ye ihtirazi kayıt ekle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: ülke dışı sevkiyat oluşturuldu. İşlem: CMR taslak doldur. Çıktı: onay sonrası PDF.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- CMR md.1; ev eşyası, posta, cenaze istisna. Belgesizlik sözleşmeyi düşürmez.

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
