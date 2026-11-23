---
tip: modul
kod: "12.03.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: zorunlu
---
# N Belge

> Kod `12.03.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- N1/N2 süre ve şube alan uygunluk notu.

## Özellikler
### MVP
- N2 belgesi bitiş tarihi
- Şube alan uyarısı var mı
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge bitişine 30 gün. İşlem: uyarı. Çıktı: yönetici bildirimi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KTY md.14 N1/N2 asgari taşıt ve m² şartları.

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
