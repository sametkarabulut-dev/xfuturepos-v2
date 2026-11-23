---
tip: modul
kod: "12.07.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# L Belge Notu

> Kod `12.07.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Depo + dağıtım birlikteyse L1/L2 hatırlatması.

## Özellikler
### MVP
- Faaliyetimiz L1 mi N mi görünüyor
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: ilk kendi araçlı dağıtım kaydı. İşlem: belge sorusu aç. Çıktı: yapılandırma kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- L1 yurt içi, L2 yurt içi+uluslararası lojistik işletmeciliği; U-ETDS L1/L2.

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
