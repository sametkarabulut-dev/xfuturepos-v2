---
tip: modul
kod: "12.07.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Pick Pack

> Kod `12.07.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Sipariş toplama, paketleme ve sevke hazır etme kuyruğu.

## Özellikler
### MVP
- Bugün 40 siparişi kuyruğa al
- Eksik stoklu siparişleri göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sipariş onaylandı. İşlem: pick listesi üret. Çıktı: toplayıcı sırası.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro API

## Mevzuat
- Doğrulama kapanışı: Mikro API açıldı: DahiliStokHareketKaydetV2. Pazaryeri seçilmedi. Stok hareketi Mikro hesabıyla, onayla yazılır.

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
