---
tip: modul
kod: "15.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sözleşme Takibi

> Kod `15.00.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Proje ve retainer bitiş tarihleri; yenileme hatırlatması (ürün aboneliği 15.08'de).

## Özellikler
### MVP
- 30 gün içinde biten retainer'ları göster
- Sözleşme yenileme taslağı hazırla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sözleşme bitişinden 14 gün önce. İşlem: sözleşme kartını oku. Çıktı: yenileme hatırlatması; onaysız müşteri iletişimi yok.

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
