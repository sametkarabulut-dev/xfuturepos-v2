---
tip: modul
kod: "16.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Tedarikçi teyidi

> Kod `16.00.03` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Kalem bazlı tedarikçi atama ve yazılı teyit durumu.

## Özellikler
### MVP
- Cumartesi ikram teyit etti mi?
- Teyitsiz tedarikçiler?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Etkinlik −72/−24 saatte teyitsiz kalemleri listeler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- WhatsApp Cloud API

## Mevzuat
- Doğrulama kapanışı: WhatsApp Cloud API dokümanı açıldı. Şablon ve işletme doğrulama gerekir. Tedarikçi metni taslaktır, gönderim onayla.

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
