---
tip: modul
kod: "12.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Teslim Kanıtı

> Kod `12.00.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır.

## Özellikler
### MVP
- Sevkiyat 34-882 teslim kanıtını aç
- Dün reddedilen teslimleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: şoför teslim işaretledi. İşlem: kanıt yoksa 30 dk sonra hatırlat. Çıktı: eksik kanıt listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Teslim ispatı; sevk e-irsaliyesi değildir.

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
