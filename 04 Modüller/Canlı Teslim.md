---
tip: modul
kod: "12.04.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Canlı Teslim

> Kod `12.04.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Teslim kodu/link, red ve iade akışı.

## Özellikler
### MVP
- 8841 için teslim kodu gönder
- Bugünkü iade kuyruğunu aç
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: kurye adreste. İşlem: tek kullanımlık kod taslağı. Çıktı: gönderim onayı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- WhatsApp Cloud API

## Mevzuat
- Alıcı iletişim verisi amaçla sınırlı; genel KVKK şablonu değil. WhatsApp Cloud API dokümanı bu oturumda açıldı (Graph API, şablon onayı, işletme doğrulama). SMS sağlayıcısı seçilmediği için dogrulanmali true kaldı. Doğrulama kapanışı: WhatsApp Cloud API dokümanı açıldı (Graph API, şablon onayı, işletme doğrulama). SMS sağlayıcısı seçilmedi. Varış metni şablon taslağıdır, gönderim onayla gider.

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
