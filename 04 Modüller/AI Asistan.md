---
tip: modul
durum: tamamlandi
katman: cekirdek
arac_turu: genel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
---
# AI Asistan

## Ne yapar
- Komut çalıştırır, taslak üretir; yüksek etkili işlem onaysız bitmez.

## Özellikler
### MVP
- Panel kaydı ve liste
- AI taslak / özet (onay kuyruğu)
### Sonraki sürüm
- Derin entegrasyonlar (kaynaklı API varsa)

## Çözdüğü ihtiyaçlar
- Sektör dosyasındaki ortak ihtiyaç satırlarına bak

## Yeniden kullanım
- **Araç türü:** genel
- Tüm 6 sektörde çekirdek.

## Entegrasyonlar
- Sektör notundaki doğrulama kapanışına göre

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
