---
tip: isletme
kod: "12-07-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Depolama ve sipariş karşılama]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "52.10"
pazar_puani: 3
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
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
  - "[[Lokasyon Stok]]"
  - "[[Pick Pack]]"
  - "[[Mal Sahibi Hesap]]"
  - "[[Sevk İrsaliye]]"
  - "[[L Belge Notu]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[X markanın stokunu göster]]"
  - "[[Sayım farkı olan gözleri listele]]"
  - "[[Bugün 40 siparişi kuyruğa al]]"
  - "[[Eksik stoklu siparişleri göster]]"
  - "[[Mart mutabakatını hazırla]]"
  - "[[Faturalanacak bekleyen işlemler]]"
  - "[[Bu çıkışta irsaliyeyi kim düzenlemeli]]"
  - "[[Faaliyetimiz L1 mi N mi görünüyor]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-07-01 · Depolama ve sipariş karşılama

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 4

## 1. Özet
Başkasının malını kabul eden, sipariş olunca toplayıp taşıyıcıya teslim eden depo.

- **İşletme sayısı:** bulunamadı
- **NACE:** 52.10

## 2. Günlük iş akışı
1. Mal kabul
2. adres
3. sayım
4. toplama
5. çıkış. Seferi taşıyıcı işler.

```mermaid
flowchart LR
  S1["Mal kabul"] --> S2
  S2["adres"] --> S3
  S3["sayım"] --> S4
  S4["toplama"] --> S5
  S5["çıkış. Seferi taşıyıcı işler."]
```

AI destek (onaylı): Kabul metninden stok hareketi ve siparişten toplama listesi yazar; irsaliye onaya kalır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Lokasyon Stok]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Pick Pack]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Mal Sahibi Hesap]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sevk İrsaliye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[L Belge Notu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[X markanın stokunu göster]]
- [[Sayım farkı olan gözleri listele]]
- [[Bugün 40 siparişi kuyruğa al]]
- [[Eksik stoklu siparişleri göster]]
- [[Mart mutabakatını hazırla]]
- [[Faturalanacak bekleyen işlemler]]
- [[Bu çıkışta irsaliyeyi kim düzenlemeli]]
- [[Faaliyetimiz L1 mi N mi görünüyor]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[Lokasyon Stok]]
- [[Pick Pack]]
- [[Mal Sahibi Hesap]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[Sevk İrsaliye]]
- [[L Belge Notu]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, Mikro API, Mikro e-İrsaliye API, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Depolama ve sipariş karşılama gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
