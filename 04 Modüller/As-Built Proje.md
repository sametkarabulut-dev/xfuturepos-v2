---
tip: modul
kod: "10.03.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# As-Built Proje

> Kod `10.03.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Uygulama sonrası çizim teslimi.

## Özellikler
### MVP
- As-built’i müellife gönder
- Bekleyen as-built’ler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Bitirme öncesi checklist

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
