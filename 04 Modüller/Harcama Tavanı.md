---
tip: modul
kod: "15.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Harcama Tavanı

> Kod `15.02.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Bütçe ve spend cap / paylaşılan kredi hattı tavanı izleme.

## Özellikler
### MVP
- Tavana yaklaşan hesapları göster
- Dün tavanı aşanları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: günlük harcama çekimi. İşlem: tanımlı tavanla karşılaştır. Çıktı: sapma uyarısı; onaysız bütçe değişikliği yok.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Meta Marketing API, Google Ads API

## Mevzuat
- Meta Business Help: paylaşılan aylık fatura kredi hattında spend cap tanımlanabilir. Doğrulama kapanışı: Meta Marketing API genel bakışı ve Google Ads erişim seviyeleri (2026-11-19) açıldı. Seviyeler Test, Explorer, Basic ve Standard. Üretim hesabına yazmak başvuru ister. Doküman doğrulandı. Canlı kampanya yazması başvuru ve insan onayı olmadan gitmez.

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
