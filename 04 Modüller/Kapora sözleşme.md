---
tip: modul
kod: "16.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kapora sözleşme

> Kod `16.00.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı.

## Özellikler
### MVP
- Yılmaz düğününün kaporası geldi mi?
- Kalan bakiyeyi hatırlat
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Vade geçen kapora/kalan için hatırlatma; kaporasız kesinleşme engeli.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- iyzico

## Mevzuat
- Doğrulama kapanışı: https://dev.iyzipay.com/ açıldı. Ödeme çağrısı insan onayı olmadan gitmez.

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
