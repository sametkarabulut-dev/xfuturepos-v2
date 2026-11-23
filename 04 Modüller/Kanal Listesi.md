---
tip: modul
kod: "15.03.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kanal Listesi

> Kod `15.03.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Müşteri kanal ve hesap envanteri.

## Özellikler
### MVP
- Müşteri kanallarını listele
- Erişimi belirsiz kanalları bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: retainer açılışı. İşlem: kanal kartı eksiklerini tara. Çıktı: eksik kanal listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
