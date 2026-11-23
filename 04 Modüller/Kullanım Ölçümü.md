---
tip: modul
kod: "15.08.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Kullanım Ölçümü

> Kod `15.08.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Ürün kullanım ve aktif hesap özeti.

## Özellikler
### MVP
- Pasif hesapları listele
- Kullanım düşen planları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: haftalık. İşlem: kullanım eşiğini uygula. Çıktı: riskli hesap listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel kaydı

## Mevzuat
- Ölçüm API'si ürüne özel; bu turda doğrulanmadı. Doğrulama kapanışı: Seçili ürün ölçüm API’si yok. Kullanım elle veya dışa aktarımla girilir.

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
