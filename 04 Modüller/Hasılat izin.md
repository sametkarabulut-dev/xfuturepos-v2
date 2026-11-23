---
tip: modul
kod: "16.04.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Hasılat izin

> Kod `16.04.03` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Bilet/hasılat özeti ve izin/güvenlik kalemleri.

## Özellikler
### MVP
- Ön satış kaç?
- Özel güvenlik başvurusu yapıldı mı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kapasite dilimine göre minimum telif notunu hatırlatır (tarife manuel).

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Elle hasılat

## Mevzuat
- Biletli etkinlikte hasılat yüzdesi/minimum bedel MESAM-MSG 4.A. Eğlence vergisi oranı bu turda netleşmedi. Doğrulama kapanışı: Biletix ve Passo için açık API bu turda yok. Hasılat elle girilir.

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
