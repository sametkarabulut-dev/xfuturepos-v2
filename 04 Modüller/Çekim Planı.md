---
tip: modul
kod: "15.04.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Çekim Planı

> Kod `15.04.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Çekim günü, ekip ve lokasyon checklist'i.

## Özellikler
### MVP
- Yarınki çekim checklist'i
- Eksik ekipmanı listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: çekimden 1 gün önce. İşlem: checklist çalıştır. Çıktı: eksik madde listesi.

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
