---
tip: modul
kod: "09.04.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# WebTapu Bağlantı

> Kod `09.04.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Değerleme uzmanı WebTapu başvuru/belge durumunun dosya bazlı takibi.

## Özellikler
### MVP
- WebTapu başvuru durumunu kaydet
- Eksik evrakları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: manuel durum güncelleme → İşlem: gecikme uyarısı → Çıktı: dosya notu

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Web Tapu değerleme portalı

## Mevzuat
- TKGM WebTapu değerleme uzmanı portalı; açık POS API doğrulanmadı. Doğrulama kapanışı: https://webtapu.tkgm.gov.tr/ açıldı. Değerleme portalı e-Devlet ve güncel TDUB kaydı ister. Açık REST yok. Başvuru paketi panelde hazırlanır.

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
