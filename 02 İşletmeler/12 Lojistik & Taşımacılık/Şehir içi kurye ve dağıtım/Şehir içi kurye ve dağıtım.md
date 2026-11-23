---
tip: isletme
kod: "12-04-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Şehir içi kurye ve dağıtım]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "53.20"
pazar_puani: 4
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
ihtiyaclar:
  - "[[Sevkiyat kartı]]"
  - "[[Navlun teklifi]]"
  - "[[Araç / şoför]]"
  - "[[Teslim kanıtı]]"
  - "[[e-Belge]]"
  - "[[U-ETDS köprüsü]]"
  - "[[Belge / yetki takibi]]"
  - "[[Kurye / durak rotası]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Sevkiyat Kartı]]"
  - "[[Navlun Teklifi]]"
  - "[[U-ETDS Köprüsü]]"
  - "[[Teslim Kanıtı]]"
  - "[[Araç Şoför]]"
  - "[[Hasar Dosyası]]"
  - "[[Araç Takip]]"
  - "[[Durak Rotası]]"
  - "[[Kurye Atama]]"
  - "[[Canlı Teslim]]"
  - "[[P Belge]]"
  - "[[Yoğunluk Paneli]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[Bugünkü 18 durağı sırala]]"
  - "[[Öğleden sonra rotayı yeniden kur]]"
  - "[[Kadıköy bölgesine 2 kurye ata]]"
  - "[[En az yüklü kuryeyi öner]]"
  - "[[8841 için teslim kodu gönder]]"
  - "[[Bugünkü iade kuyruğunu aç]]"
  - "[[P1 taşıt sayısı eksiği var mı]]"
  - "[[Dün başarısız teslim nedenlerini özetle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-04-01 · Şehir içi kurye ve dağıtım

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
İl içi veya komşu ilçelerde tasnif olmadan taşınan kurye gönderisi.

- **İşletme sayısı:** bulunamadı
- **NACE:** 53.20

## 2. Günlük iş akışı
1. Çok duraklı tur
2. teslim kanıtı
3. sık tahsilat.

```mermaid
flowchart LR
  S1["Çok duraklı tur"] --> S2
  S2["teslim kanıtı"] --> S3
  S3["sık tahsilat."]
```

AI destek (onaylı): Durakları tura dizer, teslim notundan iade çıkarır, varış metnini hazırlar.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Durak Rotası]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kurye Atama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Canlı Teslim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[P Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yoğunluk Paneli]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[Bugünkü 18 durağı sırala]]
- [[Öğleden sonra rotayı yeniden kur]]
- [[Kadıköy bölgesine 2 kurye ata]]
- [[En az yüklü kuryeyi öner]]
- [[8841 için teslim kodu gönder]]
- [[Bugünkü iade kuyruğunu aç]]
- [[P1 taşıt sayısı eksiği var mı]]
- [[Dün başarısız teslim nedenlerini özetle]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[Durak Rotası]]
- [[Kurye Atama]]
- [[Canlı Teslim]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[P Belge]]
- [[Yoğunluk Paneli]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, Google Routes API, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya), WhatsApp Cloud API
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Şehir içi kurye ve dağıtım gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
- [[U-ETDS]]
- [[Filo / TMS paketleri]]

## 9. Kaynaklar
- [[12 Lojistik & Taşımacılık – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/12-lojistik-tasimacilik.md`
