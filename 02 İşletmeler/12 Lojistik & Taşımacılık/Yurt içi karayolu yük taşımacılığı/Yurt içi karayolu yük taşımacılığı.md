---
tip: isletme
kod: "12-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Yurt içi karayolu yük taşımacılığı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "49.41"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
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
  - "[[Sefer Planı]]"
  - "[[K1 Belge]]"
  - "[[Yol Masrafı]]"
  - "[[Takograf Uyarı]]"
  - "[[Taşıma İrsaliye]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[Yarınki 5 seferi planla]]"
  - "[[34 DEF 01 i bu sefere ata]]"
  - "[[K1 belgesi ne zaman bitiyor]]"
  - "[[Taşıt kartı olmayan plakaları listele]]"
  - "[[Sefer 12 ye 2500 TL mazot ekle]]"
  - "[[Bu haftanın mazot toplamını söyle]]"
  - "[[Bugün dinlenme limiti yaklaşan şoförler]]"
  - "[[Sefer 8 için taşıma irsaliyesi taslağı]]"
  - "[[Bugün irsaliyesiz kalkan seferler]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — sevkiyat"
---
# 12-01-01 · Yurt içi karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Başka firmaların yükünü Türkiye içinde ticari olarak taşıyan filo.

- **İşletme sayısı:** bulunamadı
- **NACE:** 49.41

## 2. Günlük iş akışı
1. Yükü araca
2. SRC’li sürücüye bağlar
3. taşıma belgesini çıkarır
4. U-ETDS’ye işler
5. navlun
6. yakıtı kapatır.

```mermaid
flowchart LR
  S1["Yükü araca"] --> S2
  S2["SRC’li sürücüye bağlar"] --> S3
  S3["taşıma belgesini çıkarır"] --> S4
  S4["U-ETDS’ye işler"] --> S5
  S5["navlun"] --> S6
  S6["yakıtı kapatır."]
```

AI destek (onaylı): WhatsApp yük metninden sefer taslağı ve U-ETDS alanlarını hazırlar; gönderim onayda kalır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat Kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Navlun Teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[U-ETDS Köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sefer Planı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[K1 Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yol Masrafı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Takograf Uyarı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Taşıma İrsaliye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Sevkiyat Kartı]] + [[Navlun Teklifi]] + [[U-ETDS Köprüsü]] + [[Teslim Kanıtı]] + [[Araç Şoför]] + [[Hasar Dosyası]] + [[Araç Takip]]…

### Fonksiyonlar
- [[Yarınki 5 seferi planla]]
- [[34 DEF 01 i bu sefere ata]]
- [[K1 belgesi ne zaman bitiyor]]
- [[Taşıt kartı olmayan plakaları listele]]
- [[Sefer 12 ye 2500 TL mazot ekle]]
- [[Bu haftanın mazot toplamını söyle]]
- [[Bugün dinlenme limiti yaklaşan şoförler]]
- [[Sefer 8 için taşıma irsaliyesi taslağı]]
- [[Bugün irsaliyesiz kalkan seferler]]

### MVP
- [[Sevkiyat Kartı]]
- [[Navlun Teklifi]]
- [[U-ETDS Köprüsü]]
- [[Teslim Kanıtı]]
- [[Araç Şoför]]
- [[Sefer Planı]]
- [[K1 Belge]]
- [[Yol Masrafı]]

### Sonraki sürüm
- [[Hasar Dosyası]]
- [[Araç Takip]]
- [[Takograf Uyarı]]
- [[Taşıma İrsaliye]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle veya CSV konum, Takograf süresi, U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Yurt içi karayolu yük taşımacılığı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
