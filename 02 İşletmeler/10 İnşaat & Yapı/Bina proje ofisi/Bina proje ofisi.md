---
tip: isletme
kod: "10-06-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Bina proje ofisi]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "71.1"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 3
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
  - "[[Proje Dosya]]"
  - "[[Revizyon Sürüm]]"
  - "[[Müellif Teslim]]"
  - "[[Oda Tescil]]"
  - "[[Ruhsat Evrak]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Statik son sürümü aç]]"
  - "[[Paylaşılan linki kapat]]"
  - "[[R3 farklarını özetle]]"
  - "[[Yeni revizyon bas]]"
  - "[[YDK’ye proje teslim et]]"
  - "[[Bekleyen teslimler]]"
  - "[[Büro tescil bitişini hatırlat]]"
  - "[[Müellif hesap durumu]]"
  - "[[Ruhsat evrak paketini hazırla]]"
  - "[[Eksik paftalar]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 10-06-01 · Bina proje ofisi

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 3

## 1. Özet
Ruhsat eki mimari, statik, mekanik veya elektrik projesini büro tesciliyle üreten ofis.

- **İşletme sayısı:** bulunamadı
- **NACE:** 71.1

## 2. Günlük iş akışı
1. Çizim
2. revizyon
3. idare kaydı
4. aşamalı hizmet bedeli.

```mermaid
flowchart LR
  S1["Çizim"] --> S2
  S2["revizyon"] --> S3
  S3["idare kaydı"] --> S4
  S4["aşamalı hizmet bedeli."]
```

AI destek (onaylı): Revizyon turlarını ve eksik evrakı izleyip teslim yaklaşınca hatırlatma taslağı verir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Puantajı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Metraj Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Proje Dosya]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Revizyon Sürüm]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Müellif Teslim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Oda Tescil]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ruhsat Evrak]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kartı]] + [[Saha Puantajı]] + [[Metraj Hakediş]] + [[Şantiye Günlüğü]] + [[Malzeme Takibi]] + [[İSG Kontrol]] + [[Taşeron Sözleşme]]…

### Fonksiyonlar
- [[Statik son sürümü aç]]
- [[Paylaşılan linki kapat]]
- [[R3 farklarını özetle]]
- [[Yeni revizyon bas]]
- [[YDK’ye proje teslim et]]
- [[Bekleyen teslimler]]
- [[Büro tescil bitişini hatırlat]]
- [[Müellif hesap durumu]]
- [[Ruhsat evrak paketini hazırla]]
- [[Eksik paftalar]]

### MVP
- [[Proje Kartı]]
- [[Saha Puantajı]]
- [[Metraj Hakediş]]
- [[Şantiye Günlüğü]]
- [[Malzeme Takibi]]
- [[Proje Dosya]]
- [[Revizyon Sürüm]]
- [[Müellif Teslim]]

### Sonraki sürüm
- [[İSG Kontrol]]
- [[Taşeron Sözleşme]]
- [[Oda Tescil]]
- [[Ruhsat Evrak]]

## 5. Teknik detay
- **Entegrasyonlar:** Bulut depolama, GİB e-İrsaliye, Mobil yoklama, UYDS, UYDS ve oda kaydı, e-Fatura, İSG-KATİP ekranı, İdare ekranı, ŞANTİYE-M
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Bina proje ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
