---
tip: ihtiyac
durum: tamamlandi
kategori: yasal
moduller: []
---
# U-ETDS köprüsü

## Tanım
- 12 Lojistik & Taşımacılık ortak ihtiyaç satırı; sıklık 5/7.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[12 Lojistik & Taşımacılık]]:** 5/7 işletme türünde.

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
