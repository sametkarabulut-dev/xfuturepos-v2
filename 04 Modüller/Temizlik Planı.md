---
tip: modul
kod: "09.05.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Temizlik Planı

> Kod `09.05.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Personel & Vardiya genişlemesi: çıkış sonrası temizlik ve turnover planı.

## Özellikler
### MVP
- Bugünkü temizlik turunu planla
- Turnover gecikenleri göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: check-out → İşlem: temizlik iş emri oluştur → Çıktı: personel atama önerisi

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
