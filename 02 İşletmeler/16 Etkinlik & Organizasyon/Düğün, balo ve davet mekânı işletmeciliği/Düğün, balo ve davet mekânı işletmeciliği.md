---
tip: isletme
kod: "16-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Düğün, balo ve davet mekânı işletmeciliği]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "56.21 / 93"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
ihtiyaclar:
  - "[[Etkinlik takvimi]]"
  - "[[Kapora / sözleşme]]"
  - "[[Tedarikçi teyidi]]"
  - "[[Run-of-show]]"
  - "[[Kişi sayısı]]"
  - "[[e-Belge]]"
  - "[[Salon seans]]"
  - "[[Telif / MSG listesi]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Etkinlik takvimi]]"
  - "[[Kapora sözleşme]]"
  - "[[Tedarikçi teyidi]]"
  - "[[Run-of-show]]"
  - "[[Kişi sayısı]]"
  - "[[Salon seans]]"
  - "[[Paket menü]]"
  - "[[Mekân lisans]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[Salon B 7 Haziran öğle?]]"
  - "[[Bu hafta kesinleşenler?]]"
  - "[[250 kişi standart menü tutarı?]]"
  - "[[Kokteyl paketine pasta ekle]]"
  - "[[Müzik yayın izni bitiş?]]"
  - "[[Bu ay yenilenecek belgeler?]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — etkinlik"
---
# 16-01-01 · Düğün, balo ve davet mekânı işletmeciliği

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **4.0** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Tarihi ve salonu satan işletme. Mekânsız planlayıcı bu satırda değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 56.21 / 93

## 2. Günlük iş akışı
1. Salon takviminde opsiyon
2. kesin tarih
3. kapora
4. kişi sayısı
5. menü
6. servis ekibi.

```mermaid
flowchart LR
  S1["Salon takviminde opsiyon"] --> S2
  S2["kesin tarih"] --> S3
  S3["kapora"] --> S4
  S4["kişi sayısı"] --> S5
  S5["menü"] --> S6
  S6["servis ekibi."]
```

AI destek (onaylı): Telefonda kalmış tarih sözünü kesin ve opsiyon kayıtlarıyla karşılaştırıp ikinci sözü gösterir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapora sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Salon seans]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Paket menü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Mekân lisans]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Etkinlik takvimi]] + [[Kapora sözleşme]] + [[Tedarikçi teyidi]] + [[Run-of-show]] + [[Kişi sayısı]] + [[Salon seans]] + [[Paket menü]]…

### Fonksiyonlar
- [[Salon B 7 Haziran öğle?]]
- [[Bu hafta kesinleşenler?]]
- [[250 kişi standart menü tutarı?]]
- [[Kokteyl paketine pasta ekle]]
- [[Müzik yayın izni bitiş?]]
- [[Bu ay yenilenecek belgeler?]]

### MVP
- [[Etkinlik takvimi]]
- [[Kapora sözleşme]]
- [[Tedarikçi teyidi]]
- [[Run-of-show]]
- [[Kişi sayısı]]
- [[Salon seans]]
- [[Paket menü]]
- [[Mekân lisans]]

### Sonraki sürüm
- V2 opsiyonel araçlar

## 5. Teknik detay
- **Entegrasyonlar:** Panel seansı, Panel takvimi, WhatsApp Cloud API, iyzico
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Düğün, balo ve davet mekânı işletmeciliği gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
- [[iyzico]]
- [[Biletix / Passo]]

## 9. Kaynaklar
- [[16 Etkinlik & Organizasyon – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/16-etkinlik-organizasyon.md`
