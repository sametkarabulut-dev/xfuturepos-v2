---
tip: modul
kod: "09.02.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kira Dosyası

> Kod `09.02.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Kira sözleşmesi, süre, artış ve eklerin dosya bazlı yönetimi.

## Özellikler
### MVP
- Bitimine 60 gün kalan kiraları listele
- Bu sözleşmenin artış maddesini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: bitiş −60/−30 gün → İşlem: yenileme/uyarı taslağı → Çıktı: yönetici onay kuyruğu

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TBK 6098 konut ve çatılı işyeri kirası hükümleri.

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
