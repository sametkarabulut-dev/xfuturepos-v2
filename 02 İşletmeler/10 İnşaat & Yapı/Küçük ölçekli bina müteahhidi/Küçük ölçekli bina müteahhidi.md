---
tip: isletme
kod: "10-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Küçük ölçekli bina müteahhidi]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "KOSGEB inşaat KOBİ kümesi içinde; alt kırılım bulunamadı"
nace: "41.20"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
ihtiyaclar:
  - "[[Proje / iş kartı]]"
  - "[[Puantaj / yoklama]]"
  - "[[Metraj ve hakediş]]"
  - "[[Malzeme / stok]]"
  - "[[e-Belge]]"
  - "[[Şantiye günlüğü]]"
  - "[[Ruhsat / evrak paketi]]"
  - "[[İSG checklist]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Proje Kartı]]"
  - "[[Saha Puantajı]]"
  - "[[Metraj Hakediş]]"
  - "[[Şantiye Günlüğü]]"
  - "[[Malzeme Takibi]]"
  - "[[İSG Kontrol]]"
  - "[[Taşeron Sözleşme]]"
  - "[[Ruhsat Takibi]]"
  - "[[İş Programı]]"
  - "[[Maliyet Bütçe]]"
  - "[[Şef Atama]]"
  - "[[Keşif Teklif]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Ruhsat bekleyen projeleri göster]]"
  - "[[İskan evrak listesini çıkar]]"
  - "[[Kaba inşaat bitişini kaydır]]"
  - "[[Kritik gecikmeleri özetle]]"
  - "[[Bu ay bütçe sapmasını göster]]"
  - "[[Demir kalemini artır]]"
  - "[[Bu işe şef ata]]"
  - "[[Şefin aktif m² toplamını göster]]"
  - "[[Villaya teklif hazırla]]"
  - "[[Teklifi sözleşmeye çevir]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 10-01-01 · Küçük ölçekli bina müteahhidi

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Ruhsatlı konut, işyeri veya esaslı tadilatı kendi yetki belgesiyle üstlenen firma.

- **İşletme sayısı:** KOSGEB inşaat KOBİ kümesi içinde; alt kırılım bulunamadı
- **NACE:** 41.20

## 2. Günlük iş akışı
1. Yetki belgesi
2. şantiye şefi
3. malzeme
4. taşeron
5. yapı denetim evrakı
6. işçilik bildirimi.

```mermaid
flowchart LR
  S1["Yetki belgesi"] --> S2
  S2["şantiye şefi"] --> S3
  S3["malzeme"] --> S4
  S4["taşeron"] --> S5
  S5["yapı denetim evrakı"] --> S6
  S6["işçilik bildirimi."]
```

AI destek (onaylı): Puantaj, irsaliye ve metrajdan taşeron hakediş taslağını kurup tutarı onaya düşürür.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Puantajı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Metraj Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ruhsat Takibi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İş Programı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Maliyet Bütçe]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Şef Atama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Keşif Teklif]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kartı]] + [[Saha Puantajı]] + [[Metraj Hakediş]] + [[Şantiye Günlüğü]] + [[Malzeme Takibi]] + [[İSG Kontrol]] + [[Taşeron Sözleşme]]…

### Fonksiyonlar
- [[Ruhsat bekleyen projeleri göster]]
- [[İskan evrak listesini çıkar]]
- [[Kaba inşaat bitişini kaydır]]
- [[Kritik gecikmeleri özetle]]
- [[Bu ay bütçe sapmasını göster]]
- [[Demir kalemini artır]]
- [[Bu işe şef ata]]
- [[Şefin aktif m² toplamını göster]]
- [[Villaya teklif hazırla]]
- [[Teklifi sözleşmeye çevir]]

### MVP
- [[Proje Kartı]]
- [[Saha Puantajı]]
- [[Metraj Hakediş]]
- [[Şantiye Günlüğü]]
- [[Malzeme Takibi]]
- [[Ruhsat Takibi]]
- [[İş Programı]]
- [[Maliyet Bütçe]]

### Sonraki sürüm
- [[İSG Kontrol]]
- [[Taşeron Sözleşme]]
- [[Şef Atama]]
- [[Keşif Teklif]]

## 5. Teknik detay
- **Entegrasyonlar:** GİB e-İrsaliye, Mobil yoklama, e-Fatura, İSG-KATİP ekranı, İdare ekranı, ŞANTİYE-M
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Küçük ölçekli bina müteahhidi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
- **3 ana mesaj:**
  1. Dağınık Excel/WhatsApp yerine tek iş kaydı
  2. e-Belge ve hatırlatmalar onay kuyruğunda
  3. Sektöre özel alanlar, ortak çekirdek üzerinde
- **İtirazlar ve cevaplar:**

| İtiraz | Cevap |
|---|---|
| Zaten Excel var | Süre/uyum hatırlatması ve belge taslağı Excel’de dağılır |
| Resmi API yok | Panel kaydı + kurum portalı; uydurma entegrasyon yok |
| Pahalı | Taahhütsüz paket; yalnız kullanılan araçlar (tahmin) |

## 8. Rakipler
- [[SantiyePro]]
- [[Hakedra]]
- [[ESSantiye]]
- [[Mikro]]

## 9. Kaynaklar
- [[10 İnşaat & Yapı – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/10-insaat-yapi.md`
