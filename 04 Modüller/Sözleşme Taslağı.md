---
tip: modul
kod: "09.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: opsiyonel
---
# Sözleşme Taslağı

> Kod `09.00.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı.

## Özellikler
### MVP
- Satış yetki sözleşmesi taslağı üret
- Kira sözleşmesi madde özetini çıkar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: taslak isteği → İşlem: şablondan madde taslağı → Çıktı: inceleme kuyruğu (imza/gönderim yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TBK ve taşınmaz aracılık sözleşmesi hükümlerine uygun şablon ihtiyacı.

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
