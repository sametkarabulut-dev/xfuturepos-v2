---
tip: modul
kod: "12.02.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ro-Ro Slot

> Kod `12.02.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Feribot/Ro-Ro rezervasyonunu sevkiyat ETA’sına bağlar.

## Özellikler
### MVP
- Trieste slotunu bu sevkiyata bağla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: slot saatine 24 saat. İşlem: hatırlatma. Çıktı: operatör bildirimi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Hat kaydı

## Mevzuat
- Doğrulama kapanışı: Seçili hat yok. Slot elle girilir.

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
