---
tip: modul
kod: "15.01.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Depo Bağlantısı

> Kod `15.01.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Commit/PR kaydını iş kartına bağlama.

## Özellikler
### MVP
- Bu PR hangi işe ait?
- Açık PR'ları işlere eşle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: PR açıldı. İşlem: iş kimliği eşlemesi dene. Çıktı: eşleşmeyen PR listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- GitHub REST API, GitLab REST API v4

## Mevzuat
- GitHub REST ve GitLab /api/v4 kamuya açık. Kişisel veya uygulama tokenı gerekir; depo izni müşteri verir.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
