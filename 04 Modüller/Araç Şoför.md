---
tip: modul
kod: "12.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: opsiyonel
---
# Araç Şoför

> Kod `12.00.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi.

## Özellikler
### MVP
- SRC si 30 günde bitecek şoförleri göster
- 34 XYZ 45 plakasını Mehmet e ata
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge bitişine 15 gün. İşlem: ilgili şoförü yeni sefere önerme. Çıktı: onay isteyen uyarı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- SRC/psikoteknik ve taşıt belgesi yetki türüne bağlı (K/L/N/C/P).

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
