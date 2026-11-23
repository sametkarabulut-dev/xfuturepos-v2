---
tip: modul
kod: "15.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Proje Kapsamı

> Kod `15.00.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Sözleşme ve teklif maddeleri, kabul kriteri, kapsam dışı iş talebi kaydı; kapsam sapmasını görünür kılar.

## Özellikler
### MVP
- Bu yazışmayı kapsam maddesine çevir
- Kapsam dışı satırları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni müşteri notu veya e-posta. İşlem: maddeleri mevcut teklifle karşılaştır. Çıktı: sapma listesi ve onay bekleyen değişiklik taslağı; onaysız sözleşme oluşturulmaz.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
