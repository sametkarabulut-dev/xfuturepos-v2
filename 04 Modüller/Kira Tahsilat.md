---
tip: modul
kod: "09.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kira Tahsilat

> Kod `09.02.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Muhasebe & Gelir-Gider genişlemesi: kira vade, gecikme ve dekont eşlemesi.

## Özellikler
### MVP
- Bu ay ödenmeyen kiraları getir
- Gecikme tutarını hesapla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: vade +1 gün → İşlem: gecikme listesi → Çıktı: ihtar taslağı (gönderim onaysız yapılmaz)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Dekont ile mutabakat

## Mevzuat
- TBK m.352 iki haklı ihtar; otomatik ihtar/ödeme yok. Doğrulama kapanışı: ohvps.bkm.com.tr bu turda 500 döndü. Tek banka seçilmedi. Tahsilat kaydı panelde kalır, mutabakat dekontla yapılır.

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
