---
tip: ihtiyac
durum: tamamlandi
kategori: yasal
moduller: []
---
# Ruhsat / evrak paketi

## Tanım
- 10 İnşaat & Yapı ortak ihtiyaç satırı; sıklık 4/7.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[10 İnşaat & Yapı]]:** 4/7 işletme türünde.

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
