---
tip: ihtiyac
durum: tamamlandi
kategori: operasyon
moduller: []
---
# Run-of-show

## Tanım
- 16 Etkinlik & Organizasyon ortak ihtiyaç satırı; sıklık 6/6.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[16 Etkinlik & Organizasyon]]:** 6/6 işletme türünde.

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
