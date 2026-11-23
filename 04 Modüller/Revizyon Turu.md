---
tip: modul
kod: "15.04.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Revizyon Turu

> Kod `15.04.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Revizyon sayısı, not ve ek tur talebi.

## Özellikler
### MVP
- Revizyon notlarını maddele
- Sözleşmedeki tur aşıldı mı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: revizyon notu. İşlem: tur sayacı ile sözleşme limitini karşılaştır. Çıktı: aşım uyarısı.

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
