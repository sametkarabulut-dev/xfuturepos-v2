---
tip: modul
kod: "09.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yetki Takibi

> Kod `09.00.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- İşletme yetki belgesi, sorumlu emlak danışmanı ve belge vade takibi (TTBS).

## Özellikler
### MVP
- Yetki belgesi vadesi yaklaşanları göster
- Seviye 5 sorumlu listesi
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: vade −60/−30 gün → İşlem: yenileme hatırlatması → Çıktı: yönetici görev kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- TTBS sorgu ekranı

## Mevzuat
- Taşınmaz Ticareti Hakkında Yönetmelik; yetki belgesi TTBS üzerinden verilir/yenilenir. Doğrulama kapanışı: https://ttbs.gtb.gov.tr/ açıldı. Giriş ve yetki belgesi sorgusu var. Üçüncü parti API yok. Panel belge tarihini tutar, sorguyu kullanıcı yapar.

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
