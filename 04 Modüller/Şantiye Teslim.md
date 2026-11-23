---
tip: modul
kod: "10.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Şantiye Teslim

> Kod `10.05.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Kabul/red ve yanıt.

## Özellikler
### MVP
- Reddedilen sevkiyatları göster
- Kısmi kabul kaydet
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kısmi redde iade irsaliyesi hatırlatması

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- GİB e-İrsaliye Yanıtı

## Mevzuat
- Fiili sevk sonrası ret geçersiz

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
