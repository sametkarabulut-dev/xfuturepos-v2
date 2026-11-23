---
tip: modul
kod: "15.03.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Etkileşim Özeti

> Kod `15.03.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Dönem etkileşim ve müşteri rapor taslağı.

## Özellikler
### MVP
- Müşteri B için etkileşim özeti yaz
- Düşen kanalları işaretle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: ay sonu. İşlem: dışa aktarım veya manuel metrik girdisinden özet. Çıktı: rapor taslağı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel kaydı

## Mevzuat
- Doğrulama kapanışı: Harici API yok. Etkileşim sayıları elle veya dışa aktarımla girilir.

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
