---
tip: modul
kod: "12.04.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: zorunlu
---
# P Belge

> Kod `12.04.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- P1/P2 geçerlilik ve özmal taşıt sayısı kontrolü.

## Özellikler
### MVP
- P1 taşıt sayısı eksiği var mı
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: taşıt kaydı silindi. İşlem: asgari kapasite kontrolü. Çıktı: uyarı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- P1/P2 KTY md.14; eski dağıtım P belgeleri M1/M2 ye dönüşmüş olabilir — kurye tanımı 2025.

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
