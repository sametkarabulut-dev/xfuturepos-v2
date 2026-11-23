---
tip: modul
kod: "09.01.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Malik Yetkilendirme

> Kod `09.01.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Malikin e-Devlet üzerinden emlak işletmesine verdiği ilan yetkisinin takip kaydı.

## Özellikler
### MVP
- Yetki bekleyen portföyleri göster
- Yetki kodu süresi dolanları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yetki süresi yaklaşımı → İşlem: yenileme uyarısı → Çıktı: danışman görev kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- EİDS ilan doğrulama

## Mevzuat
- EİDS: ilan için malik yetkilendirmesi; e-Devlet oturum/yetki akışı. Doğrulama kapanışı: https://eids.ticaret.gov.tr/ açıldı. Doğrulama ilan platformuna ait. Ofis paneline açık API sitede yok. Panel yetki dosyasını tutar.

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
