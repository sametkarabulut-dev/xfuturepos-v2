---
tip: modul
kod: "09.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Gösterim Randevu

> Kod `09.00.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Mülk gösterimi randevu, çakışma kontrolü ve danışman ataması.

## Özellikler
### MVP
- Bu hafta müsait slotları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: randevu ±2 sa → İşlem: hatırlatma taslağı → Çıktı: danışmana onaylı bildirim (müşteriye otomatik SMS yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Google Calendar API

## Mevzuat
- Google Calendar API REST dokümanı 2026-09-11 tarihli genel bakışta açık. OAuth ve kullanıcı takvim izni gerekir; randevu müşteriye onaysız SMS gitmez.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
