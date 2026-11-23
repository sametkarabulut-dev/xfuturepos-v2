---
tip: modul
kod: "12.07.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Lokasyon Stok

> Kod `12.07.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Mal sahibi, SKU ve göz/adres bazlı stok; kabul ve sayım.

## Özellikler
### MVP
- X markanın stokunu göster
- Sayım farkı olan gözleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: günlük sayım kapandı. İşlem: fark listesi. Çıktı: mutabakat taslağı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Salt depolamada U-ETDS yok. Dağıtımı kendisi yapıyorsa L1/L2 veya taşımacı belgesi ayrı değerlendirilir.

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
