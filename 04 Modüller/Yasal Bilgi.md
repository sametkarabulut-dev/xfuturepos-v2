---
tip: modul
kod: "15.06.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yasal Bilgi

> Kod `15.06.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- 5651 bilgilendirme ve iletişim bilgisi kontrolü.

## Özellikler
### MVP
- 5651 bilgilendirme eksik mi?
- İletişim bilgisi güncelliğini kontrol et
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: aylık. İşlem: zorunlu bilgi alanlarını kontrol et. Çıktı: eksik bilgi listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 5651 m.3 bilgilendirme yükümlülüğü; m.4 içerik sağlayıcı sorumluluğu. Yalnız 15.06.

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
