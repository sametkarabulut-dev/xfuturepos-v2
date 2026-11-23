---
tip: modul
kod: "15.03.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İçerik Onayı

> Kod `15.03.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Brief'ten taslağa ve müşteri onayına giden kuyruk.

## Özellikler
### MVP
- Onayı bekleyen içerikleri sırala
- Brief'ten taslak üret
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: taslak hazır. İşlem: onay kuyruğuna al. Çıktı: onay bekleyen liste; onaysız yayın yok.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Reklam veya tanıtım içeriği üretiliyorsa Ticari Reklam Yönetmeliği.

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
