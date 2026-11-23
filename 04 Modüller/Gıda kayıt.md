---
tip: modul
kod: "16.06.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Gıda kayıt

> Kod `16.06.03` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- İşletme kayıt belgesi ve faaliyet konusu dosyası.

## Özellikler
### MVP
- Gıda kayıt numarası?
- Belge adresi değişti mi?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Adres/unvan değişiminde yenileme görevi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Devlet gıda kayıt

## Mevzuat
- Gıda İşletmelerinin Kayıt ve Onay Yönetmeliği; e-Devlet işletme kayıt belgesi. Gönüllü kermes istisnası ticari catering'e uygulanmaz. MSG/MESAM uygulanmaz. Doğrulama kapanışı: https://www.turkiye.gov.tr/gida-tarbil-isletme-kayit-belgesi açıldı. Hizmet e-Devlet kimliği ister. API yok. Belge tarihi panelde.

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
