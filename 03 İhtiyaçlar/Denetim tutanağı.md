---
tip: ihtiyac
durum: tamamlandi
kategori: operasyon
moduller: []
---
# Denetim tutanağı

## Tanım
- İşletmenin denetim tutanağı ihtiyacı; sektör ortak ihtiyaç tablosundan.

## Bugün nasıl çözülüyor
- Excel, WhatsApp, defter veya kurum portalı (tahmin / sektör özeti).
- Dağınık dosya; hatırlatma kişiye bağlı.

## Etkisi (zaman / para / risk)
- Zaman kaybı, kaçan tahsilat/uyum, çift kayıt.

## Çözen modüller
- İlgili sektör araç matrisi ve işletme Parçalar tablosu.

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
