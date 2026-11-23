---
tip: modul
kod: "12.06.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# TİO Belge

> Kod `12.06.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- TİO belgesi (eski R1/R2) ve G1 acente ayrımı.

## Özellikler
### MVP
- TİO belgesi bitiş tarihi
- Bu iş G1 mi TİO mu
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge bitişine 30 gün. İşlem: uyarı. Çıktı: yönetici kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Taşıma İşleri Organizatörlüğü Yönetmeliği; R türü TİO ya dönüşmüş. G1 N acenteliği.

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
