---
tip: modul
kod: "12.05.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Sigorta Teklif

> Kod `12.05.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Beyan değerine göre nakliyat sigortası maddesini teklife ekleme hatırlatması.

## Özellikler
### MVP
- Bu taşınma için sigorta tutarı öner
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: envanter değeri eşiği aştı. İşlem: teklife sigorta maddesi ekle. Çıktı: onaylı teklif satırı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Sigorta kaydı

## Mevzuat
- Doğrulama kapanışı: https://www.sbm.org.tr/ açıldı. Poliçe ve hasar sorguları sigorta ekosistemine ait. Nakliyeciye açık teklif API’si sayfada yok. Teklif kaydı elle.

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
