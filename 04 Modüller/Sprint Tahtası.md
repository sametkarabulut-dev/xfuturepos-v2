---
tip: modul
kod: "15.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sprint Tahtası

> Kod `15.01.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Sprint işleri, durum ve engeller.

## Özellikler
### MVP
- Engelli işleri listele
- Sprint bitiş özeti yaz
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sprint sonu. İşlem: tamamlanan ve kalan işleri özetle. Çıktı: sprint özeti.

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
