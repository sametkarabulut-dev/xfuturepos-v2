---
tip: modul
kod: "10.07.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Laboratuvar Numune

> Kod `10.07.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Numune ve sonuç.

## Özellikler
### MVP
- Beton numune sonuçlarını getir
- Ret edilen numuneler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sonuç gecikme uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Laboratuvar kaydı

## Mevzuat
- YDS online sonuç hedefi Doğrulama kapanışı: Seçili laboratuvar API’si yok. Numune kaydı panelde.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
