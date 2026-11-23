---
tip: modul
kod: "09.04.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Saha Envanter

> Kod `09.04.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Yerinde tespit formu, foto, ölçü ve karşılaştırılabilir örnek kayıtları.

## Özellikler
### MVP
- Bu raporun saha eksiklerini listele
- Foto setini kontrol et
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: saha yükleme → İşlem: zorunlu alan/foto kontrolü → Çıktı: eksik checklist

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TDUB/SPK rapor kalite ve bağımsızlık çerçevesi.

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
