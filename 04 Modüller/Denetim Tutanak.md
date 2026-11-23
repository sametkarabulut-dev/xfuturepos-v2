---
tip: modul
kod: "10.07.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Denetim Tutanak

> Kod `10.07.02` · [[10 İnşaat & Yapı]]

## Ne yapar
- Saha denetim ve uygunsuzluk.

## Özellikler
### MVP
- Bugünkü denetim tutanağını yaz
- Açık uygunsuzluklar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tekrar ziyaret planı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS

## Mevzuat
- 4708 md.2 Doğrulama kapanışı: UYDS adresi 500 verdi. Tutanak taslağı panelde, bildirim onayla kalır.

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
