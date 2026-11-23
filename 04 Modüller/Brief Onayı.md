---
tip: modul
kod: "15.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Brief Onayı

> Kod `15.00.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Brief, sürüm ve revizyon turu; müşteri onayı kuyruğu.

## Özellikler
### MVP
- Brief'ten iş listesi çıkar
- Açık revizyon turlarını say
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: brief veya revizyon yüklendi. İşlem: eksik alan ve açık turları tara. Çıktı: onay bekleyen iş listesi.

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
