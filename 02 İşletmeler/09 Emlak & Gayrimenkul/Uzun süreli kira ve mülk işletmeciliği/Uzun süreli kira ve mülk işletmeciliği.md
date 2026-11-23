---
tip: isletme
kod: "09-02-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Uzun süreli kira ve mülk işletmeciliği]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "İTO 68.20.02: 5.013 (kendi taşınmazını kiralama kümesi)"
nace: "68.20"
pazar_puani: 3
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
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
  - "[[Kira Dosyası]]"
  - "[[Kira Tahsilat]]"
  - "[[Bakım İş Emri]]"
  - "[[Tahliye Takvimi]]"
  - "[[Depozito Defteri]]"
rakipler:
  - "[[RE-OS]]"
  - "[[selfSite]]"
  - "[[Dijiyon]]"
  - "[[Konsiyon]]"
  - "[[NOKTApp]]"
  - "[[sahibinden]]"
fonksiyonlar:
  - "[[Bitimine 60 gün kalan kiraları listele]]"
  - "[[Bu sözleşmenin artış maddesini özetle]]"
  - "[[Bu ay ödenmeyen kiraları getir]]"
  - "[[Gecikme tutarını hesapla]]"
  - "[[Açık arızaları önceliklendir]]"
  - "[[Bu ay bakım maliyetini özetle]]"
  - "[[Tahliye tarihi yaklaşanları göster]]"
  - "[[TBK 352 sürelerini kontrol et]]"
  - "[[İade bekleyen depozitoları listele]]"
  - "[[Mahsup kalemlerini özetle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 09-02-01 · Uzun süreli kira ve mülk işletmeciliği

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Kendi veya sözleşmeyle başkasının taşınmazını uzun süreli kiracı ilişkisiyle işler.

- **İşletme sayısı:** İTO 68.20.02: 5.013 (kendi taşınmazını kiralama kümesi)
- **NACE:** 68.20

## 2. Günlük iş akışı
1. Kira sözleşmesi
2. tahsilat
3. boşalma
4. abonelik
5. bakım
6. malike hesap.

```mermaid
flowchart LR
  S1["Kira sözleşmesi"] --> S2
  S2["tahsilat"] --> S3
  S3["boşalma"] --> S4
  S4["abonelik"] --> S5
  S5["bakım"] --> S6
  S6["malike hesap."]
```

AI destek (onaylı): Vadesi gelen kirayı, bitecek sözleşmeyi ve bakım talebini malik bazında tutup dönem özetini taslaklar.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Portföy Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gösterim Randevu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İlan Doğrulama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kira Dosyası]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kira Tahsilat]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Bakım İş Emri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tahliye Takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Depozito Defteri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Portföy Kartı]] + [[Gösterim Randevu]] + [[İlan Doğrulama]] + [[Yetki Takibi]] + [[Sözleşme Taslağı]] + [[Belge Kasası]] + [[Komisyon Hesabı]]…

### Fonksiyonlar
- [[Bitimine 60 gün kalan kiraları listele]]
- [[Bu sözleşmenin artış maddesini özetle]]
- [[Bu ay ödenmeyen kiraları getir]]
- [[Gecikme tutarını hesapla]]
- [[Açık arızaları önceliklendir]]
- [[Bu ay bakım maliyetini özetle]]
- [[Tahliye tarihi yaklaşanları göster]]
- [[TBK 352 sürelerini kontrol et]]
- [[İade bekleyen depozitoları listele]]
- [[Mahsup kalemlerini özetle]]

### MVP
- [[Portföy Kartı]]
- [[Gösterim Randevu]]
- [[İlan Doğrulama]]
- [[Yetki Takibi]]
- [[Sözleşme Taslağı]]
- [[Kira Dosyası]]
- [[Kira Tahsilat]]
- [[Bakım İş Emri]]

### Sonraki sürüm
- [[Belge Kasası]]
- [[Komisyon Hesabı]]
- [[Tahliye Takvimi]]
- [[Depozito Defteri]]

## 5. Teknik detay
- **Entegrasyonlar:** Dekont ile mutabakat, EİDS Taşınmaz API, Google Calendar API, TTBS sorgu ekranı, Web Tapu emlakçı portalı
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Uzun süreli kira ve mülk işletmeciliği gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
