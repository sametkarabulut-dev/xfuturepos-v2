---
tip: modul
kod: "13.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Termin Alarm

> Kod `13.01.03` · [[13 Üretim & İmalat]]

## Ne yapar
- Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM.

## Özellikler
### MVP
- Geç kalacak işleri söyle
- Müşteri X gecikmeleri
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- SLA aşımında CRM notu önerisi

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
