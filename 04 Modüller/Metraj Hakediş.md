---
tip: modul
kod: "10.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Metraj Hakediş

> Kod `10.00.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi.

## Özellikler
### MVP
- Mart hakediş taslağını hazırla
- Kalıp m² farkını göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Dönem taslağı + metraj-puantaj tutarsızlık uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura

## Mevzuat
- Sözleşme + YDK hakediş usulü (Uygulama Yön.)

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
