---
tip: modul
kod: "10.07.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# UYDS Hazırlık

> Kod `10.07.05` · [[10 İnşaat & Yapı]]

## Ne yapar
- Resmî giriş için veri paketleme; API iddiasız.

## Özellikler
### MVP
- Aylık seviye paketini hazırla
- Eksik UYDS alanları
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik alan checklist

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS

## Mevzuat
- Kamuya açık API doğrulanmadı Doğrulama kapanışı: UYDS adresi 500 verdi. Hazırlık paketi panelde, gönderim yok.

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
