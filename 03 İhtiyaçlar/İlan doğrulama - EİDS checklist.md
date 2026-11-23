---
tip: ihtiyac
durum: tamamlandi
kategori: yasal
moduller: []
---
# İlan doğrulama / EİDS checklist

## Tanım
- 09 Emlak & Gayrimenkul ortak ihtiyaç satırı; sıklık 3/5.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, kurum portalı veya rakip paket (tahmin / sektör özeti).

## Etkisi (zaman / para / risk)
- Operasyon dağınıklığı, tahsilat/uyum kaybı riski.

## Çözen modüller
- İlgili sektör araç matrisi satırlarına bak.

## Sektörlere göre
- **[[09 Emlak & Gayrimenkul]]:** 3/5 işletme türünde.

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
