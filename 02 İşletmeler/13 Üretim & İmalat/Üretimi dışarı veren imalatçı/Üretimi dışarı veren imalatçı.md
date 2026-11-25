---
tip: isletme
kod: "13-06-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Üretimi dışarı veren imalatçı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: "C"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
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
  - "[[Fasoncu Sevk]]"
  - "[[Dönüş Kabul]]"
  - "[[Hakediş Kesinti]]"
  - "[[Fasoncu Bakiye]]"
  - "[[Çok Fasoncu]]"
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
  - "[[Fasoncu Sevk]]"
  - "[[ABC'ye 405 kg kumaş sevk et]]"
  - "[[Açık sevkler]]"
  - "[[Dönüş Kabul]]"
  - "[[ABC dönüşünü kaydet 960 adet]]"
  - "[[Ret 40]]"
  - "[[Hakediş Kesinti]]"
  - "[[ABC hakedişini kesintili hesapla]]"
  - "[[Fasoncu Bakiye]]"
  - "[[Kimde ne malzeme var]]"
  - "[[Çok Fasoncu]]"
  - "[[Kesim ABC, dikim DEF]]"
parca_sart: 30
parca_olmali: 0
parca_iyi: 4
parca_durum: tamamlandi
---
# 13-06-01 · Üretimi dışarı veren imalatçı

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 3

## 1. Özet
Kendi modelinin dönüşümünü başka atölyede yaptıran, kendi tezgâhı merkez olmayan imalatçı.

- **İşletme sayısı:** bulunamadı
- **NACE:** C
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Malzeme çıkışı
2. fason emri
3. dışarıdaki stok
4. geri kabul
5. işçilik faturası.

```mermaid
flowchart LR
  S1["Malzeme çıkışı"] --> S2
  S2["fason emri"] --> S3
  S3["dışarıdaki stok"] --> S4
  S4["geri kabul"] --> S5
  S5["işçilik faturası."]
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

34 parça · 30 şart · 0 olmalı · 4 iyi olur

### Şart (30)

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
| [[Fasoncu Sevk]] | [[Fasoncu Sevk]] | Fasoncuya malzeme sevk ve iş emri bağlama |
| [[ABC'ye 405 kg kumaş sevk et]] | [[Fasoncu Sevk]] | ABC'ye 405 kg kumaş sevk et — Fasoncuya malzeme sevk ve iş emri bağlama |
| [[Açık sevkler]] | [[Fasoncu Sevk]] | Açık sevkler — Fasoncuya malzeme sevk ve iş emri bağlama |
| [[Dönüş Kabul]] | [[Dönüş Kabul]] | Mamul kabul/ret ve reçete tüketim düşümü |
| [[ABC dönüşünü kaydet 960 adet]] | [[Dönüş Kabul]] | ABC dönüşünü kaydet 960 adet — Mamul kabul/ret ve reçete tüketim düşümü |
| [[Ret 40]] | [[Dönüş Kabul]] | Ret 40 — Mamul kabul/ret ve reçete tüketim düşümü |
| [[Hakediş Kesinti]] | [[Hakediş Kesinti]] | Fire/eksik/ret kesintili fasoncu ödemesi. Çekirdek genişleme: Muhasebe & Gelir-Gider. |
| [[ABC hakedişini kesintili hesapla]] | [[Hakediş Kesinti]] | ABC hakedişini kesintili hesapla — Fire/eksik/ret kesintili fasoncu ödemesi. Çekirdek genişleme: Muhasebe & Gelir-Gider. |

### Olmalı (0)

_Yok._

### İyi olur (4)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Fasoncu Bakiye]] | [[Fasoncu Bakiye]] | Fasoncuda kalan malzeme görünümü |
| [[Kimde ne malzeme var]] | [[Fasoncu Bakiye]] | Kimde ne malzeme var — Fasoncuda kalan malzeme görünümü |
| [[Çok Fasoncu]] | [[Çok Fasoncu]] | Operasyon bazlı farklı fasoncular |
| [[Kesim ABC, dikim DEF]] | [[Çok Fasoncu]] | Kesim ABC, dikim DEF — Operasyon bazlı farklı fasoncular |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[Mikro]]

## 7. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
