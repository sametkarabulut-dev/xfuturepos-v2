---
tip: ihtiyac
durum: tamamlandi
kategori: operasyon
moduller: []
---
# Malzeme / stok

## Tanım
- 10 İnşaat & Yapı ortak ihtiyaç satırı; sıklık 7/7.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[10 İnşaat & Yapı]]:** 7/7 işletme türünde.

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
