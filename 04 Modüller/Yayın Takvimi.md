---
tip: modul
kod: "15.03.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yayın Takvimi

> Kod `15.03.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kanal bazlı içerik takvimi ve boş slot.

## Özellikler
### MVP
- Bu hafta boş kalan günleri göster
- Onaysız içerikleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sabah. İşlem: takvim boşluklarını tara. Çıktı: boş ve onaysız slot listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Örtülü reklam riski için Ticari Reklam Yönetmeliği ilgili olabilir.

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
