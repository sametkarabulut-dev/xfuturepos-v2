---
tip: modul
kod: "15.06.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yayın Masası

> Kod `15.06.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kendi yayın planı ve boş slot.

## Özellikler
### MVP
- Yarınki yayın sırasını göster
- Boş yayın slotlarını listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sabah. İşlem: plan boşluklarını tara. Çıktı: boş slot listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 5651 m.4: içerik sağlayıcı, kullanıma sunduğu içerikten sorumludur.

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
