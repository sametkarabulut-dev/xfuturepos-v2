---
tip: modul
kod: "09.03.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Aidat İcra

> Kod `09.03.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Gecikme tazminatı hesabı ve icra dosya hazırlığı; takip başlatma insan onaylı.

## Özellikler
### MVP
- 3+ ay gecikenleri listele
- Gecikme tazminatı hesapla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: gecikme eşiği → İşlem: KMK gecikme hesabı → Çıktı: icra hazırlık dosyası (takip başlatılmaz)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYAP vatandaş ve avukat portalı

## Mevzuat
- KMK m.20 gecikme tazminatı; kesinleşmiş işletme projesi İİK m.68 belgesi niteliğinde. Doğrulama kapanışı: https://www.uyap.gov.tr/ açıldı. Vatandaş, avukat ve kurum portalları var. Site yönetimi için icra API’si yok. İhtar taslağı panelde kalır, başvuru onayla gider.

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
