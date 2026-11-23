---
tip: modul
kod: "13.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sipariş Emri

> Kod `13.01.01` · [[13 Üretim & İmalat]]

## Ne yapar
- Satış siparişinden iş emri ve termin kilidi. Çekirdek genişleme: CRM.

## Özellikler
### MVP
- Sipariş 120'yi iş emrine çevir
- Bugün teslimler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Onaylı siparişte WO önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- CRM

## Mevzuat
- Yok / panel kaydı

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
