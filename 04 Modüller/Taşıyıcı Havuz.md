---
tip: modul
kod: "12.06.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Taşıyıcı Havuz

> Kod `12.06.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Alt taşıyıcı yetki belgesi, fiyat ve performans havuzu.

## Özellikler
### MVP
- İzmir e müsait K1 taşıyıcıları öner
- XYZ Nakliyat ı kara listeye öner
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni booking. İşlem: güzergâh ve puanla öner. Çıktı: seçim onayı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TİO kendi namına fatura keser, taşımayı yaptırır.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
