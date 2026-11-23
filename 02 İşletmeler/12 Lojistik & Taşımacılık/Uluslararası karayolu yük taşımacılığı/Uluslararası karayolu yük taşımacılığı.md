---
tip: isletme
kod: "12-02-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Uluslararası karayolu yük taşımacılığı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "49.41"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
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
  - "[[CMR Belgesi]]"
  - "[[L2 Belge]]"
  - "[[Transit Dosya]]"
  - "[[Ro-Ro Slot]]"
  - "[[Geçiş İzni]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[TR DE seferi için CMR taslağı]]"
  - "[[CMR ye ihtirazi kayıt ekle]]"
  - "[[L2 geçerlilik tarihini göster]]"
  - "[[Taşıt belgesine eklenecek plakalar]]"
  - "[[Bu seferde TIR karne durumu ne]]"
  - "[[Almanya geçiş izni eksik mi]]"
  - "[[Trieste slotunu bu sevkiyata bağla]]"
  - "[[Romanya geçiş izni kalan adet]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-02-01 · Uluslararası karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 4

## 1. Özet
Sınır geçen ticari karayolu seferi; belge bugün çoğunlukla L2’dir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 49.41

## 2. Günlük iş akışı
1. CMR
2. geçiş belgesi
3. gümrük müşaviri koordinasyonu
4. dövizli navlun
5. dönüş yükü.

```mermaid
flowchart LR
  S1["CMR"] --> S2
  S2["geçiş belgesi"] --> S3
  S3["gümrük müşaviri koordinasyonu"] --> S4
  S4["dövizli navlun"] --> S5
  S5["dönüş yükü."]
```

AI destek (onaylı): Evrak listesi, belge bitiş hatırlatması ve dövizli hakediş taslağı çıkarır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[CMR Belgesi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[L2 Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Transit Dosya]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ro-Ro Slot]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Geçiş İzni]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[TR DE seferi için CMR taslağı]]
- [[CMR ye ihtirazi kayıt ekle]]
- [[L2 geçerlilik tarihini göster]]
- [[Taşıt belgesine eklenecek plakalar]]
- [[Bu seferde TIR karne durumu ne]]
- [[Almanya geçiş izni eksik mi]]
- [[Trieste slotunu bu sevkiyata bağla]]
- [[Romanya geçiş izni kalan adet]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[CMR Belgesi]]
- [[L2 Belge]]
- [[Transit Dosya]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[Ro-Ro Slot]]
- [[Geçiş İzni]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, Hat kaydı, TOBB TIR portalı, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Uluslararası karayolu yük taşımacılığı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
