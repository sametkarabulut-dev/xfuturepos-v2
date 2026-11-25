---
tip: isletme
kod: "13-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Fason işleyen atölye]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: "C"
pazar_puani: 4
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
ihtiyaclar:
  - "[[İş emri]]"
  - "[[Reçete / BOM]]"
  - "[[Fire kaydı]]"
  - "[[Depo sevk]]"
  - "[[e-Belge / e-İrsaliye]]"
  - "[[Fason mutabakat]]"
  - "[[Lot / SKT]]"
  - "[[Gıda kayıt]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[İş Emri (Üretim)]]"
  - "[[Reçete BOM]]"
  - "[[Fire Kayıt]]"
  - "[[Depo Sevk]]"
  - "[[Fason Mutabakat]]"
  - "[[Müşteri Malzeme]]"
  - "[[İşçilik Hakediş]]"
  - "[[Dönüş İrsaliye]]"
  - "[[Fire Bildirim]]"
  - "[[Kapasite Slot]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[İş Emri (Üretim)]]"
  - "[[Sipariş 452 için iş emri aç]]"
  - "[[Geciken iş emirlerini listele]]"
  - "[[Reçete BOM]]"
  - "[[Gömlek reçetesini göster]]"
  - "[[Fire oranını yüzde 5 yap]]"
  - "[[Fire Kayıt]]"
  - "[[İş emri 88 fire kaydet 12 adet]]"
  - "[[Bu hafta fire aşımı]]"
  - "[[Depo Sevk]]"
  - "[[İş emri 90 için sac çıkar]]"
  - "[[Fasoncuda kalan bakiyeyi göster]]"
  - "[[Fason Mutabakat]]"
  - "[[ABC Fason mutabakatını çıkar]]"
  - "[[Fire aşımını hakedişten kes]]"
  - "[[Müşteri Malzeme]]"
  - "[[Müşteri Y kumaş bakiyesi]]"
  - "[[Gelen malzeme kaydet]]"
  - "[[İşçilik Hakediş]]"
  - "[[Müşteri Y bu ay hakediş]]"
  - "[[Birim fiyat 4,5 TL]]"
  - "[[Dönüş İrsaliye]]"
  - "[[Mamulü müşteriye sevk et]]"
  - "[[İrsaliye hazırla]]"
  - "[[Fire Bildirim]]"
  - "[[Fireyi müşteriye bildir]]"
  - "[[Kapasite Slot]]"
  - "[[Perşembe boş slot]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 4
parca_durum: tamamlandi
---
# 13-01-01 · Fason işleyen atölye

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Başkasının malını işleyip işçilik bedeli kesen atölye.

- **İşletme sayısı:** bulunamadı
- **NACE:** C
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Gelen mal
2. işlem
3. fire mutabakatı
4. iade sevk
5. hizmet faturası.

```mermaid
flowchart LR
  S1["Gelen mal"] --> S2
  S2["işlem"] --> S3
  S3["fire mutabakatı"] --> S4
  S4["iade sevk"] --> S5
  S5["hizmet faturası."]
```

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş emri]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Reçete / BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Fire kaydı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Depo sevk]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[e-Belge / e-İrsaliye]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Fason mutabakat]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Lot / SKT]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Gıda kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |

## 4. Parçalar

35 parça · 31 şart · 0 olmalı · 4 iyi olur

### Şart (31)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Muhasebe ve Gelir-Gider]] | [[Muhasebe ve Gelir-Gider]] | Gelir, gider, cari, kasa ve banka. Sektör belgesi para kaydını buraya düşürür. |
| [[e-Fatura ve e-Arşiv]] | [[e-Fatura ve e-Arşiv]] | Satış belgesi taslağı; gönderim entegratör + onayla. |
| [[CRM]] | [[CRM]] | Kişi/firma kartı, iletişim, not; sektör alanları karta eklenir. |
| [[Personel ve Vardiya]] | [[Personel ve Vardiya]] | Personel kartı, vardiya, puantaj. Bordro/SGK kesilmez. |
| [[Raporlar]] | [[Raporlar]] | Ciro, tahsilat, açık iş ve personel özeti. |
| [[AI Asistan]] | [[AI Asistan]] | Komut çalıştırır, taslak üretir; yüksek etkili işlem onaysız bitmez. |
| [[Ayarlar]] | [[Ayarlar]] | İşletme, belge, bildirim ve entegrasyon ayarları. |
| [[İş Emri (Üretim)]] | [[İş Emri (Üretim)]] | Sipariş veya stok ihtiyacından iş emri; durum akışı; tam MES değil |
| [[Sipariş 452 için iş emri aç]] | [[İş Emri (Üretim)]] | Sipariş 452 için iş emri aç — Sipariş veya stok ihtiyacından iş emri; durum akışı; tam MES değil |
| [[Geciken iş emirlerini listele]] | [[İş Emri (Üretim)]] | Geciken iş emirlerini listele — Sipariş veya stok ihtiyacından iş emri; durum akışı; tam MES değil |
| [[Reçete BOM]] | [[Reçete BOM]] | Hammadde, birim, beklenen fire oranı; iş emrine bağlanır |
| [[Gömlek reçetesini göster]] | [[Reçete BOM]] | Gömlek reçetesini göster — Hammadde, birim, beklenen fire oranı; iş emrine bağlanır |
| [[Fire oranını yüzde 5 yap]] | [[Reçete BOM]] | Fire oranını yüzde 5 yap — Hammadde, birim, beklenen fire oranı; iş emrine bağlanır |
| [[Fire Kayıt]] | [[Fire Kayıt]] | İş emri bazlı fire; reçete toleransı ile gerçekleşen karşılaştırma |
| [[İş emri 88 fire kaydet 12 adet]] | [[Fire Kayıt]] | İş emri 88 fire kaydet 12 adet — İş emri bazlı fire; reçete toleransı ile gerçekleşen karşılaştırma |
| [[Bu hafta fire aşımı]] | [[Fire Kayıt]] | Bu hafta fire aşımı — İş emri bazlı fire; reçete toleransı ile gerçekleşen karşılaştırma |
| [[Depo Sevk]] | [[Depo Sevk]] | İş emrine bağlı malzeme çıkış/iade ve fason depo bakiyesi. Çekirdek genişleme: e-Fatura/e-Arşiv (e-irsaliye köprüsü). |
| [[İş emri 90 için sac çıkar]] | [[Depo Sevk]] | İş emri 90 için sac çıkar — İş emrine bağlı malzeme çıkış/iade ve fason depo bakiyesi. Çekirdek genişleme: e-Fatura/e-Arşiv (e-irsaliye köprüsü). |
| [[Fasoncuda kalan bakiyeyi göster]] | [[Depo Sevk]] | Fasoncuda kalan bakiyeyi göster — İş emrine bağlı malzeme çıkış/iade ve fason depo bakiyesi. Çekirdek genişleme: e-Fatura/e-Arşiv (e-irsaliye köprüsü). |
| [[Fason Mutabakat]] | [[Fason Mutabakat]] | Sevk, dönüş, kalite, fire, hakediş ve fatura eşleştirme zinciri. Çekirdek genişleme: Muhasebe & Gelir-Gider. |
| [[ABC Fason mutabakatını çıkar]] | [[Fason Mutabakat]] | ABC Fason mutabakatını çıkar — Sevk, dönüş, kalite, fire, hakediş ve fatura eşleştirme zinciri. Çekirdek genişleme: Muhasebe & Gelir-Gider. |
| [[Fire aşımını hakedişten kes]] | [[Fason Mutabakat]] | Fire aşımını hakedişten kes — Sevk, dönüş, kalite, fire, hakediş ve fatura eşleştirme zinciri. Çekirdek genişleme: Muhasebe & Gelir-Gider. |
| [[Müşteri Malzeme]] | [[Müşteri Malzeme]] | Müşteri emanet hammadde bakiyesi |
| [[Müşteri Y kumaş bakiyesi]] | [[Müşteri Malzeme]] | Müşteri Y kumaş bakiyesi — Müşteri emanet hammadde bakiyesi |
| [[Gelen malzeme kaydet]] | [[Müşteri Malzeme]] | Gelen malzeme kaydet — Müşteri emanet hammadde bakiyesi |
| [[İşçilik Hakediş]] | [[İşçilik Hakediş]] | Kabul adedi üzerinden işçilik faturalama. Çekirdek genişleme: e-Fatura/e-Arşiv. |
| [[Müşteri Y bu ay hakediş]] | [[İşçilik Hakediş]] | Müşteri Y bu ay hakediş — Kabul adedi üzerinden işçilik faturalama. Çekirdek genişleme: e-Fatura/e-Arşiv. |
| [[Birim fiyat 4,5 TL]] | [[İşçilik Hakediş]] | Birim fiyat 4,5 TL — Kabul adedi üzerinden işçilik faturalama. Çekirdek genişleme: e-Fatura/e-Arşiv. |
| [[Dönüş İrsaliye]] | [[Dönüş İrsaliye]] | Mamulün müşteriye sevki. Çekirdek genişleme: e-Fatura/e-Arşiv. |
| [[Mamulü müşteriye sevk et]] | [[Dönüş İrsaliye]] | Mamulü müşteriye sevk et — Mamulün müşteriye sevki. Çekirdek genişleme: e-Fatura/e-Arşiv. |
| [[İrsaliye hazırla]] | [[Dönüş İrsaliye]] | İrsaliye hazırla — Mamulün müşteriye sevki. Çekirdek genişleme: e-Fatura/e-Arşiv. |

### Olmalı (0)

_Yok._

### İyi olur (4)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Fire Bildirim]] | [[Fire Bildirim]] | Müşteri malzemesinde fire raporu |
| [[Fireyi müşteriye bildir]] | [[Fire Bildirim]] | Fireyi müşteriye bildir — Müşteri malzemesinde fire raporu |
| [[Kapasite Slot]] | [[Kapasite Slot]] | Haftalık iş kabul slotları |
| [[Perşembe boş slot]] | [[Kapasite Slot]] | Perşembe boş slot — Haftalık iş kabul slotları |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[Mikro]]

## 7. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
