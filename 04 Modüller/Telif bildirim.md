---
tip: modul
kod: "16.04.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Telif bildirim

> Kod `16.04.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- MESAM-MSG konser/etkinlik lisansı ve eser listesi taslağı.

## Özellikler
### MVP
- MSG bildirim taslağı hazırla
- Eser listesi eksik sanatçı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Gösteri −15 gün telif/bildirim hatırlatması.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- MSG bildirim formu

## Mevzuat
- FSEK m.41/52; MSG konser-etkinlik bildirimi; 2026 MESAM-MSG ortak tarife 4.A. Doğrulama kapanışı: https://msg.org.tr/dagitim/konser-etkinlik-bildirimi açıldı. Bildirim form ve eser listesiyle. API yok. Taslak panelde, iletim kullanıcıda.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[16 Etkinlik & Organizasyon]]:** sektör/alt araç

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
