---
tip: modul
kod: "12.01.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# K1 Belge

> Kod `12.01.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi.

## Özellikler
### MVP
- K1 belgesi ne zaman bitiyor
- Taşıt kartı olmayan plakaları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge bitişine 30 gün. İşlem: ilgili plakaları sefere kapalı öner. Çıktı: yönetici uyarısı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KTY K1; U-ETDS bildirimi K1 için zorunlu (12.00.03).

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
