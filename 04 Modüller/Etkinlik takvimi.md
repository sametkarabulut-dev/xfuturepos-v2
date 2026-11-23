---
tip: modul
kod: "16.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Etkinlik takvimi

> Kod `16.00.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli.

## Özellikler
### MVP
- 15 Haziran akşam boş mu?
- Aynı tarihe iki opsiyon var mı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Opsiyon süresi bitince düşürür; kesin+opsiyon çakışmasını işaretler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel takvimi

## Mevzuat
- Doğrulama kapanışı: Salon yazılımı geliştirici dokümanı bu turda yok. Takvim panelin kendi kaydıdır, dış sync yok.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[16 Etkinlik & Organizasyon]]:** sektör/alt araç

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
