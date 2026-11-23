---
tip: modul
kod: "13.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# SKT Parti

> Kod `13.05.02` · [[13 Üretim & İmalat]]

## Ne yapar
- SKT/TETT ve FEFO sevk

## Özellikler
### MVP
- SKT'si 7 gün kalanlar
- FEFO ile sevk
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- SKT yaklaşınca uyarı; eski lot önceliği

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- 13.00.04

## Mevzuat
- Parti tanımlama/etiketleme (m.39)

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

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
