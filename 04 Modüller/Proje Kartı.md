---
tip: modul
kod: "10.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Proje Kartı

> Kod `10.00.01` · [[10 İnşaat & Yapı]]

## Ne yapar
- Şantiye/iş kartı; CRM genişlemesi.

## Özellikler
### MVP
- Aktif şantiyeleri listele
- C blok projesini askıya al
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Ruhsat/bitiş ve eksik şef-usta uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 3194; ŞANTİYE-M tanımlı yönetmelikler

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
