---
tip: modul
kod: "09.00.06"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Belge Kasası

> Kod `09.00.06` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi.

## Özellikler
### MVP
- Bu portföyün tapu belgelerini listele
- Süresi dolan belgeleri bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge yükleme → İşlem: tip/tarih etiketleme → Çıktı: eksik belge uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Web Tapu emlakçı portalı

## Mevzuat
- TKGM WebTapu süreçleri; POS için açık API doğrulanmadı. Doğrulama kapanışı: https://webtapu.tkgm.gov.tr/ açıldı. Emlakçı portalı e-Devlet şifresi ve TTBS yetkisi ister. Kurum portalı TKGM protokolü ister. KOBİ yazılımına açık REST yok. Belge kasası dosya yükler.

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
