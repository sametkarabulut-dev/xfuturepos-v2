---
tip: isletme
kod: "09-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Turizm amaçlı kısa süreli konut işletmeciliği]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro']
isletme_sayisi: "bulunamadı"
nace: "55.20"
pazar_puani: 2
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 3
aciliyet_puani: 4
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
  - "[[Rezervasyon Takvim]]"
  - "[[İzin Belgesi]]"
  - "[[Misafir Checkin]]"
  - "[[Temizlik Planı]]"
  - "[[Kanal Yönetimi]]"
  - "[[Dinamik Fiyat]]"
rakipler:
  - "[[RE-OS]]"
  - "[[selfSite]]"
  - "[[Dijiyon]]"
  - "[[Konsiyon]]"
  - "[[NOKTApp]]"
  - "[[sahibinden]]"
fonksiyonlar:
  - "[[Bu hafta doluluk göster]]"
  - "[[Çakışan rezervasyonları bul]]"
  - "[[İzin belgesi olmayan üniteleri listele]]"
  - "[[Denetim hatırlatmalarını göster]]"
  - "[[Bugün check-in listesini getir]]"
  - "[[Eksik kimlik kaydı olanları göster]]"
  - "[[Bugünkü temizlik turunu planla]]"
  - "[[Turnover gecikenleri göster]]"
  - "[[Kanallardaki fiyat farklarını göster]]"
  - "[[Overbooking riskini tara]]"
  - "[[Yarın için fiyat öner]]"
  - "[[Düşük doluluk günlerini işaretle]]"
fiyat_araligi: "bulunamadı — kanal/PMS bandı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 09-05-01 · Turizm amaçlı kısa süreli konut işletmeciliği

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 2 · ödeme 4 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 4

## 1. Özet
İzin belgeli konutu yüz güne kadar kiraya veren malik işletme veya yüksek nitelikli konutta yönetim işletmesi.

- **İşletme sayısı:** bulunamadı
- **NACE:** 55.20

## 2. Günlük iş akışı
1. İzin belgesi
2. plaket
3. doluluk
4. giriş-çıkış
5. temizlik sırası.

```mermaid
flowchart LR
  S1["İzin belgesi"] --> S2
  S2["plaket"] --> S3
  S3["doluluk"] --> S4
  S4["giriş-çıkış"] --> S5
  S5["temizlik sırası."]
```

AI destek (onaylı): Giriş, çıkış ve temizliği takvime yazar; yüz gün ve izin belgesi süresini hatırlatır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Portföy Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gösterim Randevu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İlan Doğrulama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Rezervasyon Takvim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İzin Belgesi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Misafir Checkin]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Temizlik Planı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kanal Yönetimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Portföy Kartı]] + [[Gösterim Randevu]] + [[İlan Doğrulama]] + [[Yetki Takibi]] + [[Sözleşme Taslağı]] + [[Belge Kasası]] + [[Komisyon Hesabı]]…

### Fonksiyonlar
- [[Bu hafta doluluk göster]]
- [[Çakışan rezervasyonları bul]]
- [[İzin belgesi olmayan üniteleri listele]]
- [[Denetim hatırlatmalarını göster]]
- [[Bugün check-in listesini getir]]
- [[Eksik kimlik kaydı olanları göster]]
- [[Bugünkü temizlik turunu planla]]
- [[Turnover gecikenleri göster]]
- [[Kanallardaki fiyat farklarını göster]]
- [[Overbooking riskini tara]]
- [[Yarın için fiyat öner]]
- [[Düşük doluluk günlerini işaretle]]

### MVP
- [[Portföy Kartı]]
- [[Gösterim Randevu]]
- [[İlan Doğrulama]]
- [[Yetki Takibi]]
- [[Sözleşme Taslağı]]
- [[Rezervasyon Takvim]]
- [[İzin Belgesi]]
- [[Misafir Checkin]]

### Sonraki sürüm
- [[Belge Kasası]]
- [[Komisyon Hesabı]]
- [[Temizlik Planı]]
- [[Kanal Yönetimi]]
- [[Dinamik Fiyat]]

## 5. Teknik detay
- **Entegrasyonlar:** EİDS Taşınmaz API, Google Calendar API, Kanal durumu (elle), Panel kaydı, TTBS sorgu ekranı, Web Tapu emlakçı portalı, e-Devlet izin belgesi
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı — kanal/PMS bandı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Turizm amaçlı kısa süreli konut işletmeciliği gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
