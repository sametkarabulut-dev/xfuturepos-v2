---
tip: ihtiyac
durum: tamamlandi
kategori: operasyon
moduller: []
---
# Filo konum

## Tanım
- 12 Lojistik & Taşımacılık ortak ihtiyaç satırı; sıklık 3/7.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[12 Lojistik & Taşımacılık]]:** 3/7 işletme türünde.

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
