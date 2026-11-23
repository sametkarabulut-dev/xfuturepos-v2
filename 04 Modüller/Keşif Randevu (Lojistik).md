---
tip: modul
kod: "12.05.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Keşif Randevu (Lojistik)

> Kod `12.05.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Keşif günü, kat, asansör, m²; teklife girdi. CRM çekirdeğine iş akışı bağlar.

## Özellikler
### MVP
- Cumartesi keşiflerini listele
- Bu keşfi tamamlandı yap
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: keşif +1 gün teklif yok. İşlem: hatırlatma. Çıktı: satıcı kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
