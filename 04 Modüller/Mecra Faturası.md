---
tip: modul
kod: "15.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Mecra Faturası

> Kod `15.05.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Mecra faturası ile plan/sipariş satırı eşlemesi.

## Özellikler
### MVP
- Faturası gelmeyen siparişleri bul
- Fatura farklarını listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: fatura girildi. İşlem: plan satırıyla eşle. Çıktı: fark listesi.

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
