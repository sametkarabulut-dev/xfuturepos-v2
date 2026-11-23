---
tip: modul
kod: "15.08.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Abonelik Yenileme

> Kod `15.08.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Abonelik dönemi, yenileme ve churn riski.

## Özellikler
### MVP
- 14 gün içinde yenilenecekleri göster
- Ödemesi geciken abonelikleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yenilemeden 14 gün önce. İşlem: abonelik kartını oku. Çıktı: yenileme ve churn listesi; onaysız tahsilat yok.

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
