---
tip: modul
kod: "15.07.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Uzaktan Bağlantı

> Kod `15.07.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Uzaktan erişim kaydı ve oturum notu.

## Özellikler
### MVP
- Açık uzaktan erişimleri listele
- Oturum notunu özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: oturum kapandı. İşlem: not taslağı üret. Çıktı: oturum özeti.

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
