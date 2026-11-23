---
tip: modul
kod: "10.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Şantiye Günlüğü

> Kod `10.00.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Operasyonel günlük; Şantiye-M hazırlık (otomatik API yok).

## Özellikler
### MVP
- Bugünkü günlük raporu hazırla
- Son 7 gün çalışılmayan günleri göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Akşam hatırlatma; foto-konum eksik uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- ŞANTİYE-M

## Mevzuat
- Şantiye şefi defter; Şantiyem mobil zorunlu alanlar Doğrulama kapanışı: https://cbs.csb.gov.tr/santiye-m-yazilimi-113510 açıldı. ŞANTİYE-M e-Devlet hizmeti; müteahhit ve şantiye şefi modülü anlatılıyor. Üçüncü parti API yok. Günlük panelde, bakanlık girişi kullanıcıda.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
