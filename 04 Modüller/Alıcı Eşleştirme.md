---
tip: modul
kod: "09.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Alıcı Eşleştirme

> Kod `09.01.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- CRM genişlemesi: bütçe/lokasyon/özellik ile portföy adayı skorlama.

## Özellikler
### MVP
- Bu alıcıya 5 aday öner
- Bütçe 8–10M eşleşmeleri getir
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni alıcı ihtiyacı → İşlem: skorlu aday listesi → Çıktı: danışman onayına aday kartları

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
