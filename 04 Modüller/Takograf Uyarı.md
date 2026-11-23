---
tip: modul
kod: "12.01.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Takograf Uyarı

> Kod `12.01.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Planlanan sürüşe göre dinlenme/süre aşımı hatırlatması; cihaz API’si bağlanmadan çalışır.

## Özellikler
### MVP
- Bugün dinlenme limiti yaklaşan şoförler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: planlanan sürüş eşiği aşıldı. İşlem: uyarı kartı aç. Çıktı: şoför ve operatör bildirimi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Takograf süresi

## Mevzuat
- Takograf yükümlülüğü araç sınıfına bağlı; entegrasyon doğrulanmadı. Doğrulama kapanışı: https://www.dijitaltakograf.gov.tr/ bu turda 500 verdi. Cihaz API’si seçilmedi. Süre hatırlatması panelde.

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
