---
tip: modul
kod: "15.07.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kurulum Kaydı

> Kod `15.07.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kurulum, eğitim ve müşteri ortam kaydı.

## Özellikler
### MVP
- Kurulum checklist'i çıkar
- Eğitimi tamamlanmayanları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: kurulum kapandı. İşlem: checklist çalıştır. Çıktı: eksik adım listesi.

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
