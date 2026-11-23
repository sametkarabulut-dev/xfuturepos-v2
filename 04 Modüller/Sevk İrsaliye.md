---
tip: modul
kod: "12.07.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Sevk İrsaliye

> Kod `12.07.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Mal çıkışında sevk/e-irsaliye yükümlüsünü (mal sahibi vs lojistik merkez) ayırt eden checklist.

## Özellikler
### MVP
- Bu çıkışta irsaliyeyi kim düzenlemeli
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: mal çıkış emri. İşlem: rol checklist. Çıktı: uyarı kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro e-İrsaliye API

## Mevzuat
- 509 VUK e-irsaliye sevk irsaliyesidir; e-Fatura + 10M TL (2021+) veya sektör listeleri. Taşımacının taşıma irsaliyesi ayrı belgedir. Lojistik merkez senaryoları GİB kılavuzuna göre değişir. Doğrulama kapanışı: Mikro API açıldı: IrsaliyeKaydetV2 ve EIrsaliyeGonderV2. Ham GİB ucu KOBİ’ye açık değil. Taslak panelde, GİB gönderimi Mikro hesabı ve onayla.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
