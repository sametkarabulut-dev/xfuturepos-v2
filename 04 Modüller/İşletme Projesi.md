---
tip: modul
kod: "09.03.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İşletme Projesi

> Kod `09.03.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Yıllık gelir-gider, avans/aidat dağılımı; geçici proje ve genel kurul onayı.

## Özellikler
### MVP
- Geçici işletme projesi taslağı oluştur
- Yeniden değerleme üst sınırını uygula
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yılbaşı veya onaylı proje yok → İşlem: geçici proje taslağı + artış tavanı → Çıktı: kurul onayına sunum paketi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KMK m.37; 7579 ile genel kurul onayı ve geçici projede yeniden değerleme tavanı.

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
