---
tip: modul
kod: "12.04.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kurye Atama

> Kod `12.04.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Bölge ve kapasiteye göre kurye/araç ataması. Personel çekirdeği genişlemesi.

## Özellikler
### MVP
- Kadıköy bölgesine 2 kurye ata
- En az yüklü kuryeyi öner
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni paket. İşlem: en az yüklü uygun kuryeyi öner. Çıktı: atama onayı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- P1 asgari 5 özmal; P1* ≤3 taşıt esnaf istisnası.

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
