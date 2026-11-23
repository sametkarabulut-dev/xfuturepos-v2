---
tip: modul
kod: "15.04.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Hak Listesi

> Kod `15.04.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Teslimde mali hakların ayrı ayrı gösterildiği kontrol listesi.

## Özellikler
### MVP
- Hak listesi eksik mi?
- 5846 hak maddelerini doldur
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: teslim veya onay. İşlem: hak satırlarını kontrol et. Çıktı: eksik hak listesi; onaysız hak devri yok.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 5846 sayılı Kanun m.48 mali hakların devri/ruhsat; m.52 yazılı şekil ve hakların ayrı ayrı gösterilmesi.

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
