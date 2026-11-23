---
tip: modul
kod: "12.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Navlun Teklifi

> Kod `12.00.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı.

## Özellikler
### MVP
- İstanbul Ankara 12 ton navlun taslağı çıkar
- Geçen ayki ABC fiyatını bu işe kopyala
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni sevkiyat talebi. İşlem: son benzer işlerden medyan navlun öner. Çıktı: taslak teklif; otomatik gönderim yok.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
