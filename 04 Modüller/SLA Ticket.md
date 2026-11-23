---
tip: modul
kod: "15.07.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# SLA Ticket

> Kod `15.07.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Talep kuyruğu, SLA süre ve öncelik.

## Özellikler
### MVP
- SLA'sı dolmak üzere ticket'ları göster
- Eksik bilgili talepleri ayıkla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni ticket. İşlem: eksik alan ve SLA riskini işaretle. Çıktı: risk ve eksik listesi.

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
