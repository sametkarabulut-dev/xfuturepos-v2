---
tip: modul
kod: "15.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Teknik Kapsam

> Kod `15.01.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Teknik madde takibi ve kapsam dışı geliştirme işareti.

## Özellikler
### MVP
- Bu talep teklifte var mı?
- Kapsam dışı PR'ları işaretle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni talep. İşlem: teklif maddeleriyle eşle. Çıktı: kapsam dışı uyarı.

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
