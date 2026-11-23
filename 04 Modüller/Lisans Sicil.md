---
tip: modul
kod: "09.04.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Lisans Sicil

> Kod `09.04.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Uzman/yardımcı SPL lisans durumu ve yenileme eğitim takibi.

## Özellikler
### MVP
- Askı riski olan lisansları listele
- Yenileme eğitimi yaklaşanları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yenileme −45 gün veya askı → İşlem: uyarı → Çıktı: uyum görev kartı (rapor ataması engel önerisi)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- SPL sicil kaydı

## Mevzuat
- SPL Gayrimenkul/Konut Değerleme Lisansı; yenileme eğitimi yoksa lisans askıya alınabilir. Doğrulama kapanışı: https://www.spl.com.tr/ açıldı. Lisans ve sicil kurumu. Sayfada üçüncü parti sicil API’si yok. Lisans tarihi elle tutulur.

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
