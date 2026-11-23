---
tip: modul
kod: "09.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İzin Belgesi

> Kod `09.05.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- e-Devlet izin belgesi numarası, yenileme ve iptal risk takibi.

## Özellikler
### MVP
- İzin belgesi olmayan üniteleri listele
- Denetim hatırlatmalarını göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: belge yok veya vade → İşlem: uyum uyarısı → Çıktı: yönetici checklist (başvuru otomatik yapılmaz)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Devlet izin belgesi

## Mevzuat
- Konutların Turizm Amaçlı Kiralanması Yönetmeliği: başvurular yalnızca e-Devlet. Doğrulama kapanışı: 7464 kapsamı e-Devlet izin hizmetidir. Bu turda hizmete ait açık API dokümanı yok. Panel izin belgesi tarihini tutar.

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
