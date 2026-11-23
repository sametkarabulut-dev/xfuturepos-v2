---
tip: modul
kod: "10.07.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# YİBF Takip

> Kod `10.07.01` · [[10 İnşaat & Yapı]]

## Ne yapar
- YİBF ve atama takibi.

## Özellikler
### MVP
- Aktif YİBF listesi
- Şefi istifa eden işler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Personel değişiklik hatırlatması

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS

## Mevzuat
- 4708; UYDS işlemleri Doğrulama kapanışı: UYDS adresi 500 verdi. YİBF paketi panelde tutulur, sistem girişi kullanıcıda.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
