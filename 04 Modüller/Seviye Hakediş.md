---
tip: modul
kod: "10.07.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Seviye Hakediş

> Kod `10.07.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Form-22 seviye hakedişi.

## Özellikler
### MVP
- Seviye hakedişini hazırla
- Ödeme bekleyenler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- 1 ay içinde hakediş hatırlatması

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS

## Mevzuat
- Yapı Denetimi Uygulama Yön. md.28 Doğrulama kapanışı: UYDS adresi 500 verdi. e-Fatura çekirdek modüldedir. Seviye tutarı panelde hesaplanır, resmi giriş kullanıcıda.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
