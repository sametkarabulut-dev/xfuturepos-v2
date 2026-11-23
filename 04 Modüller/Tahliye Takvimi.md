---
tip: modul
kod: "09.02.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Tahliye Takvimi

> Kod `09.02.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Tahliye taahhüdü tarihleri ve yasal süre hatırlatmaları.

## Özellikler
### MVP
- Tahliye tarihi yaklaşanları göster
- TBK 352 sürelerini kontrol et
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: taahhüt tarihi −15 gün → İşlem: süre checklist'i → Çıktı: hukuk/yönetici notu (icra başlatma yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TBK m.352: teslimden sonra yazılı tahliye taahhüdü; 1 ay içinde takip/dava.

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
