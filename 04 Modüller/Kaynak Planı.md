---
tip: modul
kod: "15.00.06"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Kaynak Planı

> Kod `15.00.06` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kişi-hafta kapasite ve aşırı yük görünümü.

## Özellikler
### MVP
- Kim aşırı yüklü?
- Sprint için boş kapasiteyi bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni iş atandı. İşlem: kapasiteyi güncelle. Çıktı: aşırı yük uyarısı.

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
