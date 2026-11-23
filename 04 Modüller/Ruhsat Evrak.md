---
tip: modul
kod: "10.06.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ruhsat Evrak

> Kod `10.06.05` · [[10 İnşaat & Yapı]]

## Ne yapar
- İdare evrak paketi.

## Özellikler
### MVP
- Ruhsat evrak paketini hazırla
- Eksik paftalar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksikte gönderim engeli önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- İdare ekranı

## Mevzuat
- Yerel imar Doğrulama kapanışı: Tek ulusal ruhsat API’si yok. Evrak listesi panelde, başvuru idare ekranında.

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
