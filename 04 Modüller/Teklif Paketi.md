---
tip: modul
kod: "15.00.07"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Teklif Paketi

> Kod `15.00.07` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Teklif şablonu, kalem ve süre varsayımları.

## Özellikler
### MVP
- Benzer tekliften taslak üret
- Kapsam maddelerini numaralandır
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni fırsat. İşlem: geçmiş tekliflerden taslak kur. Çıktı: teklif taslağı; onaysız gönderim yok.

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
