---
tip: modul
kod: "12.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Eşya Envanter

> Kod `12.05.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Oda bazlı eşya listesi, kırılgan ve demontaj notları.

## Özellikler
### MVP
- Salon envanterine piyano ekle
- Fotoğrafı eksik odaları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: keşif kapandı. İşlem: eksik oda checklist. Çıktı: tamamla uyarısı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Uluslararası ev eşyası CMR kapsamı dışında (CMR md.1).

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
