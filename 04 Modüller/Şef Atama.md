---
tip: modul
kod: "10.01.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Şef Atama

> Kod `10.01.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Şantiye şefi atama ve limit.

## Özellikler
### MVP
- Bu işe şef ata
- Şefin aktif m² toplamını göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Limit aşımı uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- ŞANTİYE-M

## Mevzuat
- Şantiye Şefliği Yönetmeliği Doğrulama kapanışı: ŞANTİYE-M sayfası açıldı. Şantiye şefliği modülü e-Devlet hizmeti. Atama kaydı panelde, sistem girişi kullanıcıda.

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
