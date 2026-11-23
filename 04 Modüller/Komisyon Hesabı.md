---
tip: modul
kod: "09.00.07"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Komisyon Hesabı

> Kod `09.00.07` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi.

## Özellikler
### MVP
- Bu satışta komisyon tutarını hesapla
- Danışman payını göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: işlem kapandı → İşlem: komisyon satırı önerisi → Çıktı: muhasebe onay kuyruğu (otomatik tahsilat yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Aracılık ücreti sözleşmeye bağlı; faaliyet yetki belgesi şartına tabi işletmeler.

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
