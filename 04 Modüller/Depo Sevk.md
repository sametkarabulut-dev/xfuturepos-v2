---
tip: modul
kod: "13.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Depo Sevk

> Kod `13.00.04` · [[13 Üretim & İmalat]]

## Ne yapar
- İş emrine bağlı malzeme çıkış/iade ve fason depo bakiyesi. Çekirdek genişleme: e-Fatura/e-Arşiv (e-irsaliye köprüsü).

## Özellikler
### MVP
- İş emri 90 için sac çıkar
- Fasoncuda kalan bakiyeyi göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sevk sonrası bakiye güncelleme; e-irsaliye zorunluluk bayrağı önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro e-İrsaliye API

## Mevzuat
- VUK 509: ciro 10M vs GTİP 72/73 ayrı eşikler Doğrulama kapanışı: Mikro API açıldı: IrsaliyeKaydetV2 ve EIrsaliyeGonderV2. Gönderim onayla.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

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
