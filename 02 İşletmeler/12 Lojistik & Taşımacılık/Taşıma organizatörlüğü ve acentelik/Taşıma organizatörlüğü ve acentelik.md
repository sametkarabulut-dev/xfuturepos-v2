---
tip: isletme
kod: "12-06-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Taşıma organizatörlüğü ve acentelik]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "52.29"
pazar_puani: 2
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
aciliyet_puani: 3
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
  - "[[Taşıyıcı Havuz]]"
  - "[[Booking Emri]]"
  - "[[TİO Belge]]"
  - "[[Multimodal Plan]]"
  - "[[Marj Paneli]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[İzmir e müsait K1 taşıyıcıları öner]]"
  - "[[XYZ Nakliyat ı kara listeye öner]]"
  - "[[Booking 220 yi Ahmet Lojistik e ver]]"
  - "[[Açık bookingleri listele]]"
  - "[[TİO belgesi bitiş tarihi]]"
  - "[[Bu iş G1 mi TİO mu]]"
  - "[[Mersin liman bacağını plana ekle]]"
  - "[[Bu ay negatif marjlı işleri göster]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-06-01 · Taşıma organizatörlüğü ve acentelik

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 2 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 3

## 1. Özet
Kendi filosunu işletmeden kendi adına taşıma yaptıran TİO, komisyoncu veya G acentesi.

- **İşletme sayısı:** bulunamadı
- **NACE:** 52.29

## 2. Günlük iş akışı
1. Teklif
2. taşıyıcı ayırma
3. taşıma belgesi
4. izleme
5. navlun farkı.

```mermaid
flowchart LR
  S1["Teklif"] --> S2
  S2["taşıyıcı ayırma"] --> S3
  S3["taşıma belgesi"] --> S4
  S4["izleme"] --> S5
  S5["navlun farkı."]
```

AI destek (onaylı): Müşteri mesajından taşıma türü, evrak listesi ve navlun teklifi kurar; iş emri onayla gider.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Taşıyıcı Havuz]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Booking Emri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[TİO Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Multimodal Plan]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Marj Paneli]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[İzmir e müsait K1 taşıyıcıları öner]]
- [[XYZ Nakliyat ı kara listeye öner]]
- [[Booking 220 yi Ahmet Lojistik e ver]]
- [[Açık bookingleri listele]]
- [[TİO belgesi bitiş tarihi]]
- [[Bu iş G1 mi TİO mu]]
- [[Mersin liman bacağını plana ekle]]
- [[Bu ay negatif marjlı işleri göster]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[Taşıyıcı Havuz]]
- [[Booking Emri]]
- [[TİO Belge]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[Multimodal Plan]]
- [[Marj Paneli]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, Hat planı, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Taşıma organizatörlüğü ve acentelik gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
