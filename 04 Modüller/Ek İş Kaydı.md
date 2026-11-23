---
tip: modul
kod: "10.02.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ek İş Kaydı

> Kod `10.02.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Yazılı ek iş/revizyon.

## Özellikler
### MVP
- Ek iş kaydı aç
- Onaysız ek işleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sözlü talimat risk uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TBK ek protokol

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
