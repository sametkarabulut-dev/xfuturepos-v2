---
tip: isletme
kod: "09-04-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Gayrimenkul değerleme kuruluşu]]"
durum: tamamlandi
olcek: ['kucuk-orta']
isletme_sayisi: "İTO 68.32.01: 1.174"
nace: "68.32"
pazar_puani: 2
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
aciliyet_puani: 3
ihtiyaclar:
  - "[[Yetki belgesi ve sorumlu danışman takibi]]"
  - "[[Portföy kartı ve medya]]"
  - "[[Gösterim randevusu]]"
  - "[[Tahsilat / aidat / komisyon kaydı]]"
  - "[[e-Belge]]"
  - "[[Sözleşme taslağı]]"
  - "[[İlan doğrulama / EİDS checklist]]"
  - "[[Kira tahsilat ve dekont]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Portföy Kartı]]"
  - "[[Gösterim Randevu]]"
  - "[[İlan Doğrulama]]"
  - "[[Yetki Takibi]]"
  - "[[Sözleşme Taslağı]]"
  - "[[Belge Kasası]]"
  - "[[Komisyon Hesabı]]"
  - "[[Rapor İş Akışı]]"
  - "[[Lisans Sicil]]"
  - "[[Saha Envanter]]"
  - "[[Emsal Analizi]]"
  - "[[WebTapu Bağlantı]]"
rakipler:
  - "[[RE-OS]]"
  - "[[selfSite]]"
  - "[[Dijiyon]]"
  - "[[Konsiyon]]"
  - "[[NOKTApp]]"
  - "[[sahibinden]]"
fonksiyonlar:
  - "[[İmzada bekleyen raporları getir]]"
  - "[[Bu banka için SLA ihlallerini göster]]"
  - "[[Askı riski olan lisansları listele]]"
  - "[[Yenileme eğitimi yaklaşanları göster]]"
  - "[[Bu raporun saha eksiklerini listele]]"
  - "[[Foto setini kontrol et]]"
  - "[[3 emsal öner]]"
  - "[[Düzeltme katsayılarını özetle]]"
  - "[[WebTapu başvuru durumunu kaydet]]"
  - "[[Eksik evrakları listele]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 09-04-01 · Gayrimenkul değerleme kuruluşu

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **2.4** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 2 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 3

## 1. Özet
SPK III-62.3 listesindeki anonim şirket rapor üretir; banka raporu için ayrıca BDDK listesi gerekir.

- **İşletme sayısı:** İTO 68.32.01: 1.174
- **NACE:** 68.32

## 2. Günlük iş akışı
1. İş emri
2. yerinde inceleme
3. emsal
4. sorumlu uzman kontrolü.

```mermaid
flowchart LR
  S1["İş emri"] --> S2
  S2["yerinde inceleme"] --> S3
  S3["emsal"] --> S4
  S4["sorumlu uzman kontrolü."]
```

AI destek (onaylı): Kimlik, konum ve standart başlıkları taslaklar; değer kanaati ve imza lisanslı uzmanda kalır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Portföy Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gösterim Randevu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İlan Doğrulama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Rapor İş Akışı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Lisans Sicil]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Envanter]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Emsal Analizi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[WebTapu Bağlantı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Portföy Kartı]] + [[Gösterim Randevu]] + [[İlan Doğrulama]] + [[Yetki Takibi]] + [[Sözleşme Taslağı]] + [[Belge Kasası]] + [[Komisyon Hesabı]]…

### Fonksiyonlar
- [[İmzada bekleyen raporları getir]]
- [[Bu banka için SLA ihlallerini göster]]
- [[Askı riski olan lisansları listele]]
- [[Yenileme eğitimi yaklaşanları göster]]
- [[Bu raporun saha eksiklerini listele]]
- [[Foto setini kontrol et]]
- [[3 emsal öner]]
- [[Düzeltme katsayılarını özetle]]
- [[WebTapu başvuru durumunu kaydet]]
- [[Eksik evrakları listele]]

### MVP
- [[Portföy Kartı]]
- [[Gösterim Randevu]]
- [[İlan Doğrulama]]
- [[Yetki Takibi]]
- [[Sözleşme Taslağı]]
- [[Rapor İş Akışı]]
- [[Lisans Sicil]]
- [[Saha Envanter]]

### Sonraki sürüm
- [[Belge Kasası]]
- [[Komisyon Hesabı]]
- [[Emsal Analizi]]
- [[WebTapu Bağlantı]]

## 5. Teknik detay
- **Entegrasyonlar:** EİDS Taşınmaz API, Google Calendar API, SPL sicil kaydı, TTBS sorgu ekranı, Web Tapu değerleme portalı, Web Tapu emlakçı portalı
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Gayrimenkul değerleme kuruluşu gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
- [[RE-OS]]
- [[selfSite]]
- [[Dijiyon]]
- [[Konsiyon]]
- [[NOKTApp]]
- [[sahibinden]]

## 9. Kaynaklar
- [[09 Emlak & Gayrimenkul – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/09-emlak-gayrimenkul.md`
