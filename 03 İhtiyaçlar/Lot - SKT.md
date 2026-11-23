---
tip: ihtiyac
durum: tamamlandi
kategori: yasal
moduller: []
---
# Lot / SKT

## Tanım
- 13 Üretim & İmalat ortak ihtiyaç satırı; sıklık 1/6.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[13 Üretim & İmalat]]:** 1/6 işletme türünde.

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
