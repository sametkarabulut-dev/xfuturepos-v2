---
tip: modul
kod: "15.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Saat Kullanımı

> Kod `15.00.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Faturalanabilir ve faturalanamayan saat kaydı; proje veya retainer ile eşleme.

## Özellikler
### MVP
- Bu haftanın faturalanamayan saatini özetle
- Müşteri X için faturalanabilir saati göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: gün sonu. İşlem: zaman kayıtlarını proje ve müşteriye bağla. Çıktı: faturalanamayan saat özeti ve fatura taslağı önerisi; onaysız tahsilat yok.

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
