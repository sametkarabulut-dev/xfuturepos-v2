---
tip: isletme
kod: "10-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Yapı malzemesi bayii]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "46.83"
pazar_puani: 3
odeme_puani: 4
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
  - "[[Sipariş Stok]]"
  - "[[Sevkiyat İrsaliye]]"
  - "[[Şantiye Teslim]]"
  - "[[Fiyat Liste]]"
  - "[[Cari Limit]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Çimento stoğunu söyle]]"
  - "[[X şantiyesi için 20 ton ayır]]"
  - "[[Yarınki sevkiyatları listele]]"
  - "[[e-İrsaliye kes]]"
  - "[[Reddedilen sevkiyatları göster]]"
  - "[[Kısmi kabul kaydet]]"
  - "[[Demir fiyatını güncelle]]"
  - "[[A carisine özel liste]]"
  - "[[Limit aşan carileri göster]]"
  - "[[B carisine limit koy]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 10-05-01 · Yapı malzemesi bayii

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 3

## 1. Özet
Çimento, tuğla, seramik, doğrama veya sıhhi malzeme stoklayıp şantiyeye vadeli satan toptancı.

- **İşletme sayısı:** bulunamadı
- **NACE:** 46.83

## 2. Günlük iş akışı
1. Stok
2. fiyat
3. sipariş
4. şantiye teslimatı
5. cari risk
6. irsaliye.

```mermaid
flowchart LR
  S1["Stok"] --> S2
  S2["fiyat"] --> S3
  S3["sipariş"] --> S4
  S4["şantiye teslimatı"] --> S5
  S5["cari risk"] --> S6
  S6["irsaliye."]
```

AI destek (onaylı): Mesajla gelen siparişi şantiye adresi ve cari limit ile irsaliye taslağına çevirir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saha Puantajı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Metraj Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sipariş Stok]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sevkiyat İrsaliye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Şantiye Teslim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fiyat Liste]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Cari Limit]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kartı]] + [[Saha Puantajı]] + [[Metraj Hakediş]] + [[Şantiye Günlüğü]] + [[Malzeme Takibi]] + [[İSG Kontrol]] + [[Taşeron Sözleşme]]…

### Fonksiyonlar
- [[Çimento stoğunu söyle]]
- [[X şantiyesi için 20 ton ayır]]
- [[Yarınki sevkiyatları listele]]
- [[e-İrsaliye kes]]
- [[Reddedilen sevkiyatları göster]]
- [[Kısmi kabul kaydet]]
- [[Demir fiyatını güncelle]]
- [[A carisine özel liste]]
- [[Limit aşan carileri göster]]
- [[B carisine limit koy]]

### MVP
- [[Proje Kartı]]
- [[Saha Puantajı]]
- [[Metraj Hakediş]]
- [[Şantiye Günlüğü]]
- [[Malzeme Takibi]]
- [[Sipariş Stok]]
- [[Sevkiyat İrsaliye]]
- [[Şantiye Teslim]]

### Sonraki sürüm
- [[İSG Kontrol]]
- [[Taşeron Sözleşme]]
- [[Fiyat Liste]]
- [[Cari Limit]]

## 5. Teknik detay
- **Entegrasyonlar:** GİB e-İrsaliye, GİB e-İrsaliye Yanıtı, Mobil yoklama, e-Fatura, İSG-KATİP ekranı, ŞANTİYE-M
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Yapı malzemesi bayii gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
