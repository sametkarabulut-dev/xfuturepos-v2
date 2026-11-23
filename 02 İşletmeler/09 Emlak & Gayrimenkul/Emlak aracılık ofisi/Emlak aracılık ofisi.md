---
tip: isletme
kod: "09-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Emlak aracılık ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "İTO 68.31.01: 14.828 (İstanbul oda; TR geneli yok)"
nace: "68.31"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
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
  - "[[Alıcı Eşleştirme]]"
  - "[[Malik Yetkilendirme]]"
  - "[[Teklif Takibi]]"
  - "[[Ofis Portföy Payı]]"
  - "[[Piyasa Bandı]]"
rakipler:
  - "[[RE-OS]]"
  - "[[selfSite]]"
  - "[[Dijiyon]]"
  - "[[Konsiyon]]"
  - "[[NOKTApp]]"
  - "[[sahibinden]]"
fonksiyonlar:
  - "[[Bu alıcıya 5 aday öner]]"
  - "[[Bütçe 8–10M eşleşmeleri getir]]"
  - "[[Yetki bekleyen portföyleri göster]]"
  - "[[Yetki kodu süresi dolanları listele]]"
  - "[[Açık teklifleri sırala]]"
  - "[[Bu portföyün son teklifini özetle]]"
  - "[[Ortak portföyleri listele]]"
  - "[[Paylaşım kuralını özetle]]"
  - "[[Bu daire için fiyat bandı öner]]"
  - "[[Son 30 gün benzer satılıkları özetle]]"
fiyat_araligi: "bulunamadı — tahmin: 790–2.500₺/ay CRM bandı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 09-01-01 · Emlak aracılık ofisi

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Yetki belgeli işletme, başkasına ait konut, işyeri, arsa veya devre mülke komisyonla aracılık eder.

- **İşletme sayısı:** İTO 68.31.01: 14.828 (İstanbul oda; TR geneli yok)
- **NACE:** 68.31

## 2. Günlük iş akışı
1. Yetkilendirme dosyası
2. EİDS izinli ilan
3. talep eşleme
4. yer gösterme
5. yazılı teklif
6. aracılık sözleşmesi.

```mermaid
flowchart LR
  S1["Yetkilendirme dosyası"] --> S2
  S2["EİDS izinli ilan"] --> S3
  S3["talep eşleme"] --> S4
  S4["yer gösterme"] --> S5
  S5["yazılı teklif"] --> S6
  S6["aracılık sözleşmesi."]
```

AI destek (onaylı): Dosyadan ilan metni ve talep listesi kurar; yetki bitişi ile ilanı üç gün içinde kaldırma süresini hatırlatır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Portföy Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gösterim Randevu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İlan Doğrulama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Alıcı Eşleştirme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Malik Yetkilendirme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Teklif Takibi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ofis Portföy Payı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Piyasa Bandı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Portföy Kartı]] + [[Gösterim Randevu]] + [[İlan Doğrulama]] + [[Yetki Takibi]] + [[Sözleşme Taslağı]] + [[Belge Kasası]] + [[Komisyon Hesabı]]…

### Fonksiyonlar
- [[Bu alıcıya 5 aday öner]]
- [[Bütçe 8–10M eşleşmeleri getir]]
- [[Yetki bekleyen portföyleri göster]]
- [[Yetki kodu süresi dolanları listele]]
- [[Açık teklifleri sırala]]
- [[Bu portföyün son teklifini özetle]]
- [[Ortak portföyleri listele]]
- [[Paylaşım kuralını özetle]]
- [[Bu daire için fiyat bandı öner]]
- [[Son 30 gün benzer satılıkları özetle]]

### MVP
- [[Portföy Kartı]]
- [[Gösterim Randevu]]
- [[İlan Doğrulama]]
- [[Yetki Takibi]]
- [[Sözleşme Taslağı]]
- [[Alıcı Eşleştirme]]
- [[Malik Yetkilendirme]]
- [[Teklif Takibi]]

### Sonraki sürüm
- [[Belge Kasası]]
- [[Komisyon Hesabı]]
- [[Ofis Portföy Payı]]
- [[Piyasa Bandı]]

## 5. Teknik detay
- **Entegrasyonlar:** EİDS Taşınmaz API, EİDS ilan doğrulama, Google Calendar API, TTBS sorgu ekranı, Web Tapu emlakçı portalı, sahibinden kurumsal aktarım (sözleşmeli)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı — tahmin: 790–2.500₺/ay CRM bandı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Emlak aracılık ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
