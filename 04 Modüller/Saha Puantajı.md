---
tip: modul
kod: "10.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Saha Puantajı

> Kod `10.00.02` · [[10 İnşaat & Yapı]]

## Ne yapar
- Firma-ekip-blok puantaj; Personel genişlemesi. Çekirdek genişleme: Personel & Vardiya.

## Özellikler
### MVP
- Bugün B blokta kaç kişi var?
- Elektrik ekibi puantajını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik çıkış ve beyan-kayıt fark uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mobil yoklama

## Mevzuat
- 4857 çalışma süreleri kaydı Doğrulama kapanışı: Seçili PDKS markası yok. MVP yoklaması panelden girilir.

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
