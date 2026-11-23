---
tip: modul
kod: "09.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Teklif Takibi

> Kod `09.01.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Alıcı teklifleri, karşı teklif ve durum pipeline'ı.

## Özellikler
### MVP
- Açık teklifleri sırala
- Bu portföyün son teklifini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni teklif → İşlem: karşılaştırma özeti → Çıktı: danışman bildirim taslağı (taraflara otomatik iletim yok)

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
