---
tip: isletme
kod: "10-04-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Tadilat ve basit onarım]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "43.3"
pazar_puani: 4
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
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
  - "[[Keşif Randevu]]"
  - "[[Teklif Onay]]"
  - "[[İş Takvimi]]"
  - "[[Önce Sonra]]"
  - "[[Garanti Servis]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Yarın keşif randevusu koy]]"
  - "[[Bu hafta keşifleri listele]]"
  - "[[Banyo tadilat teklifi gönder]]"
  - "[[Onaylanan teklifleri göster]]"
  - "[[Mutfak işini perşembeye al]]"
  - "[[Çakışan işleri bul]]"
  - "[[Önce-sonra albümü oluştur]]"
  - "[[Eksik foto mahalleri]]"
  - "[[Garanti kaydı aç]]"
  - "[[Bu ay servis çağrıları]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 10-04-01 · Tadilat ve basit onarım

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Taşıyıcıya dokunmayan boya, tesisat tamiri ve iç yenilemeyi doğrudan müşteriye yapan ekip.

- **İşletme sayısı:** bulunamadı
- **NACE:** 43.3

## 2. Günlük iş akışı
1. Keşif
2. teklif
3. malzeme
4. kısa ekip
5. iş bitince fatura.

```mermaid
flowchart LR
  S1["Keşif"] --> S2
  S2["teklif"] --> S3
  S3["malzeme"] --> S4
  S4["kısa ekip"] --> S5
  S5["iş bitince fatura."]
```

AI destek (onaylı): Müşteri mesajındaki iş tarifinden kalemli teklif ve malzeme listesi taslağı çıkarır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Puantajı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Metraj Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Keşif Randevu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Teklif Onay]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İş Takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Önce Sonra]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Garanti Servis]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kartı]] + [[Saha Puantajı]] + [[Metraj Hakediş]] + [[Şantiye Günlüğü]] + [[Malzeme Takibi]] + [[İSG Kontrol]] + [[Taşeron Sözleşme]]…

### Fonksiyonlar
- [[Yarın keşif randevusu koy]]
- [[Bu hafta keşifleri listele]]
- [[Banyo tadilat teklifi gönder]]
- [[Onaylanan teklifleri göster]]
- [[Mutfak işini perşembeye al]]
- [[Çakışan işleri bul]]
- [[Önce-sonra albümü oluştur]]
- [[Eksik foto mahalleri]]
- [[Garanti kaydı aç]]
- [[Bu ay servis çağrıları]]

### MVP
- [[Proje Kartı]]
- [[Saha Puantajı]]
- [[Metraj Hakediş]]
- [[Şantiye Günlüğü]]
- [[Malzeme Takibi]]
- [[Keşif Randevu]]
- [[Teklif Onay]]
- [[İş Takvimi]]

### Sonraki sürüm
- [[İSG Kontrol]]
- [[Taşeron Sözleşme]]
- [[Önce Sonra]]
- [[Garanti Servis]]

## 5. Teknik detay
- **Entegrasyonlar:** GİB e-İrsaliye, Mobil yoklama, Takvim, e-Fatura, İSG-KATİP ekranı, ŞANTİYE-M
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Tadilat ve basit onarım gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
