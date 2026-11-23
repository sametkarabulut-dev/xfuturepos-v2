---
tip: modul
kod: "15.07.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Destek Sözleşmesi

> Kod `15.07.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Bakım sözleşmesi süresi ve yenileme.

## Özellikler
### MVP
- Biten destek sözleşmelerini göster
- Yenileme hatırlatması hazırla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: bitişten 30 gün önce. İşlem: sözleşme kartını oku. Çıktı: yenileme listesi; onaysız fatura yok.

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
