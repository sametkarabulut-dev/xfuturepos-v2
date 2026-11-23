---
tip: modul
kod: "15.01.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kabul Kontrolü

> Kod `15.01.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kabul kriteri, UAT ve imza öncesi eksikler.

## Özellikler
### MVP
- Kabul için eksikleri çıkar
- UAT notlarını maddele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: iş kabulde. İşlem: kriter ile kanıtı karşılaştır. Çıktı: eksik kabul listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
