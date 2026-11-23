---
tip: modul
kod: "09.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Portföy Kartı

> Kod `09.00.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Satış/kira/işletme için taşınmaz kimliği, özellikler, durum ve medya yönetimi.

## Özellikler
### MVP
- Boşta satılık daireleri listele
- Kadıköy 3+1 portföyleri getir
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni kart kaydı → İşlem: eksik alan/foto kontrolü → Çıktı: tamamlanacak alan checklist'i (yayın yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
