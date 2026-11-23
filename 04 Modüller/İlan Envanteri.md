---
tip: modul
kod: "15.06.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İlan Envanteri

> Kod `15.06.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Kendi alan/zaman envanteri ve satış kaydı.

## Özellikler
### MVP
- Satılmamış envanteri göster
- Bu hafta satılan ilanları özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: satış veya rezervasyon. İşlem: envanteri güncelle. Çıktı: müsait envanter.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Ticari Reklam Yönetmeliği: mecra kuruluşu.

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
