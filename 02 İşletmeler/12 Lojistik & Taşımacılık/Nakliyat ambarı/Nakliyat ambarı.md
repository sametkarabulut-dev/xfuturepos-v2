---
tip: isletme
kod: "12-03-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Nakliyat ambarı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "52.29"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
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
  - "[[Parsiyel Toplama]]"
  - "[[Hat Seferi]]"
  - "[[Ambar Stok]]"
  - "[[G1 Acente]]"
  - "[[N Belge]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[Ankara hattına 4 parça ekle]]"
  - "[[Bugün kabul edilen parçaları listele]]"
  - "[[İstanbul Ankara hattı doluluk oranı]]"
  - "[[Hat 3 ü kalkışa kapat]]"
  - "[[Raf A-12 de ne var]]"
  - "[[3 gündür bekleyen parçalar]]"
  - "[[G1 sözleşmeli ambarları listele]]"
  - "[[N2 belgesi bitiş tarihi]]"
  - "[[Şube alan uyarısı var mı]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-03-01 · Nakliyat ambarı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 4

## 1. Özet
Parça yükü şubede kabul edip aynı yöne giden hat aracında birleştiren işletme.

- **İşletme sayısı:** bulunamadı
- **NACE:** 52.29

## 2. Günlük iş akışı
1. Kabul
2. ölçüm
3. hat seçimi
4. aktarma
5. varış şubesinden teslim.

```mermaid
flowchart LR
  S1["Kabul"] --> S2
  S2["ölçüm"] --> S3
  S3["hat seçimi"] --> S4
  S4["aktarma"] --> S5
  S5["varış şubesinden teslim."]
```

AI destek (onaylı): Parça yükü hat aracına ağırlık ve hacimle önerir; yanlış şube ve eksik tahsilatı işaretler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Parsiyel Toplama]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Hat Seferi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ambar Stok]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[G1 Acente]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[N Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[Ankara hattına 4 parça ekle]]
- [[Bugün kabul edilen parçaları listele]]
- [[İstanbul Ankara hattı doluluk oranı]]
- [[Hat 3 ü kalkışa kapat]]
- [[Raf A-12 de ne var]]
- [[3 gündür bekleyen parçalar]]
- [[G1 sözleşmeli ambarları listele]]
- [[N2 belgesi bitiş tarihi]]
- [[Şube alan uyarısı var mı]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[Parsiyel Toplama]]
- [[Hat Seferi]]
- [[Ambar Stok]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[G1 Acente]]
- [[N Belge]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, U-ETDS eşya SOAP, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Nakliyat ambarı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
