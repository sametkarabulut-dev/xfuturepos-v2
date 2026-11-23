---
tip: isletme
kod: "10-03-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Mekanik ve elektrik tesisat taşeronu]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "43.2"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
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
  - "[[Keşif Metraj]]"
  - "[[Test Devreye]]"
  - "[[Malzeme Poz]]"
  - "[[As-Built Proje]]"
  - "[[Revizyon Talep]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Kollektör hattı metrajını güncelle]]"
  - "[[Elektrik poz farkını göster]]"
  - "[[Isıtma basınç testini kaydet]]"
  - "[[Açık testleri listele]]"
  - "[[Yangın pompalarını teslim al]]"
  - "[[Eksik vana listesi]]"
  - "[[As-built’i müellife gönder]]"
  - "[[Bekleyen as-built’ler]]"
  - "[[RFI aç]]"
  - "[[Cevapsız RFI’ları göster]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 10-03-01 · Mekanik ve elektrik tesisat taşeronu

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 4

## 1. Özet
Bina içi elektrik, sıhhi tesisat, ısıtma-iklimlendirme ve asansör montajını proje ve malzeme ile yürüten firma.

- **İşletme sayısı:** bulunamadı
- **NACE:** 43.2

## 2. Günlük iş akışı
1. Projeden malzeme çıkarma
2. tedarik
3. montaj
4. test
5. hakediş.

```mermaid
flowchart LR
  S1["Projeden malzeme çıkarma"] --> S2
  S2["tedarik"] --> S3
  S3["montaj"] --> S4
  S4["test"] --> S5
  S5["hakediş."]
```

AI destek (onaylı): Tesisat kalemlerinden malzeme listesi ve hakediş taslağı üretir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Puantajı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Metraj Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Keşif Metraj]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Test Devreye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Malzeme Poz]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[As-Built Proje]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Revizyon Talep]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kartı]] + [[Saha Puantajı]] + [[Metraj Hakediş]] + [[Şantiye Günlüğü]] + [[Malzeme Takibi]] + [[İSG Kontrol]] + [[Taşeron Sözleşme]]…

### Fonksiyonlar
- [[Kollektör hattı metrajını güncelle]]
- [[Elektrik poz farkını göster]]
- [[Isıtma basınç testini kaydet]]
- [[Açık testleri listele]]
- [[Yangın pompalarını teslim al]]
- [[Eksik vana listesi]]
- [[As-built’i müellife gönder]]
- [[Bekleyen as-built’ler]]
- [[RFI aç]]
- [[Cevapsız RFI’ları göster]]

### MVP
- [[Proje Kartı]]
- [[Saha Puantajı]]
- [[Metraj Hakediş]]
- [[Şantiye Günlüğü]]
- [[Malzeme Takibi]]
- [[Keşif Metraj]]
- [[Test Devreye]]
- [[Malzeme Poz]]

### Sonraki sürüm
- [[İSG Kontrol]]
- [[Taşeron Sözleşme]]
- [[As-Built Proje]]
- [[Revizyon Talep]]

## 5. Teknik detay
- **Entegrasyonlar:** GİB e-İrsaliye, Mobil yoklama, e-Fatura, e-İrsaliye, İSG-KATİP ekranı, ŞANTİYE-M
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Mekanik ve elektrik tesisat taşeronu gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
