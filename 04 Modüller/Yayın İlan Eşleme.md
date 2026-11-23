---
tip: modul
kod: "15.06.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Yayın İlan Eşleme

> Kod `15.06.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Satılmış ilanın yayın slotuna denk gelmesi.

## Özellikler
### MVP
- Yayına denk gelmeyen ilanları bul
- Çakışan slotları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yayın öncesi. İşlem: ilan ile slotu eşle. Çıktı: çakışma veya eksik listesi.

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
