---
tip: isletme
kod: "13-04-02"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Siparişe göre kısa çevrim atölye]]"
durum: tamamlandi
olcek: [mikro, kucuk-orta]
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: "C"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 3
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
  - "[[Sipariş Emri]]"
  - "[[Atölye Kuyruk]]"
  - "[[Termin Alarm]]"
  - "[[Tezgah Yük]]"
  - "[[Revize Sipariş]]"
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
  - "[[Sipariş Emri]]"
  - "[[Sipariş 120'yi iş emrine çevir]]"
  - "[[Bugün teslimler]]"
  - "[[Atölye Kuyruk]]"
  - "[[Torna kuyruğunu sırala]]"
  - "[[Acil işi öne al]]"
  - "[[Termin Alarm]]"
  - "[[Geç kalacak işleri söyle]]"
  - "[[Müşteri X gecikmeleri]]"
  - "[[Tezgah Yük]]"
  - "[[Bu hafta freze doluluk]]"
  - "[[Revize Sipariş]]"
  - "[[Sipariş 55 miktarı 80 yap]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 4
parca_durum: tamamlandi
---
# 13-04-02 · Tamir ve revizyon atölyesi

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 3

## 1. Özet
Kısa çevrimli tamir/revizyon iş emri; aynı çekirdek, farklı iş tipi.

- **İşletme sayısı:** bulunamadı
- **NACE:** C
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Kabul
2. Teşhis
3. İş emri
4. Teslim

```mermaid
flowchart LR
  S1["Kabul"] --> S2
  S2["Teşhis"] --> S3
  S3["İş emri"] --> S4
  S4["Teslim"]
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
| [[Sipariş Emri]] | [[Sipariş Emri]] | Satış siparişinden iş emri ve termin kilidi. Çekirdek genişleme: CRM. |
| [[Sipariş 120'yi iş emrine çevir]] | [[Sipariş Emri]] | Sipariş 120'yi iş emrine çevir — Satış siparişinden iş emri ve termin kilidi. Çekirdek genişleme: CRM. |
| [[Bugün teslimler]] | [[Sipariş Emri]] | Bugün teslimler — Satış siparişinden iş emri ve termin kilidi. Çekirdek genişleme: CRM. |
| [[Atölye Kuyruk]] | [[Atölye Kuyruk]] | Termin öncelikli basit iş sırası |
| [[Torna kuyruğunu sırala]] | [[Atölye Kuyruk]] | Torna kuyruğunu sırala — Termin öncelikli basit iş sırası |
| [[Acil işi öne al]] | [[Atölye Kuyruk]] | Acil işi öne al — Termin öncelikli basit iş sırası |
| [[Termin Alarm]] | [[Termin Alarm]] | Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM. |
| [[Geç kalacak işleri söyle]] | [[Termin Alarm]] | Geç kalacak işleri söyle — Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM. |
| [[Müşteri X gecikmeleri]] | [[Termin Alarm]] | Müşteri X gecikmeleri — Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM. |

### Olmalı (0)

_Yok._

### İyi olur (4)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Tezgah Yük]] | [[Tezgah Yük]] | Basit yük görünümü; MES kapasite planı değil |
| [[Bu hafta freze doluluk]] | [[Tezgah Yük]] | Bu hafta freze doluluk — Basit yük görünümü; MES kapasite planı değil |
| [[Revize Sipariş]] | [[Revize Sipariş]] | Üretimde miktar/ölçü değişikliği onayı |
| [[Sipariş 55 miktarı 80 yap]] | [[Revize Sipariş]] | Sipariş 55 miktarı 80 yap — Üretimde miktar/ölçü değişikliği onayı |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarına bak; açık API yoksa panel kaydı.
- **Ana ekranlar:** İş listesi · Kart · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay)`

## 6. Rakipler
- [[Mikro]]

## 7. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
