---
tip: modul
kod: "09.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İlan Doğrulama

> Kod `09.00.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- İlan öncesi kimlik/yetki doğrulama durumu ve yayın checklist'i; EİDS uyumu.

## Özellikler
### MVP
- Bu ilanın EİDS durumunu kontrol et
- Yetkisiz ilanları işaretle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yayın talebi → İşlem: yetki/doğrulama bayrağı kontrolü → Çıktı: yayına uygun/uygunsuz özeti (otomatik yayın yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- EİDS Taşınmaz API

## Mevzuat
- Taşınmaz Ticareti Hakkında Yönetmelik kapsamında EİDS ile ilan kimlik/yetki doğrulama.

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
