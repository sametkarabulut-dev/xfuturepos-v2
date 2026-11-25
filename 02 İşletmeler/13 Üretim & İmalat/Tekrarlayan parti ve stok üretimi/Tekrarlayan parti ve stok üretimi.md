---
tip: isletme
kod: "13-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Tekrarlayan parti ve stok üretimi]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: "C"
pazar_puani: 4
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
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
  - "[[Parti Plan]]"
  - "[[Lot Barkod]]"
  - "[[Min Max]]"
  - "[[Verim Rapor]]"
  - "[[Alternatif Reçete]]"
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
  - "[[Parti Plan]]"
  - "[[SKU-A için 500'lük parti aç]]"
  - "[[Bu ay planı]]"
  - "[[Lot Barkod]]"
  - "[[Lot L-2411 oluştur]]"
  - "[[Lot L-2411 nereye gitti]]"
  - "[[Min Max]]"
  - "[[Min altına düşenleri listele]]"
  - "[[Min 200 yap]]"
  - "[[Verim Rapor]]"
  - "[[SKU-B verim raporu]]"
  - "[[Alternatif Reçete]]"
  - "[[Alternatif reçeteyi uygula]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 4
parca_durum: tamamlandi
---
# 13-05-01 · Tekrarlayan parti ve stok üretimi

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.4** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 4 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 4

## 1. Özet
Kendi stok kodunu aynı reçeteyle partiler halinde yenileyen işletme.

- **İşletme sayısı:** bulunamadı
- **NACE:** C
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Sabit reçete
2. parti miktarı
3. fire payı
4. ambar eşiği
5. sevkiyat.

```mermaid
flowchart LR
  S1["Sabit reçete"] --> S2
  S2["parti miktarı"] --> S3
  S3["fire payı"] --> S4
  S4["ambar eşiği"] --> S5
  S5["sevkiyat."]
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
| [[Parti Plan]] | [[Parti Plan]] | Stok/talep ile parti ve iş emri |
| [[SKU-A için 500'lük parti aç]] | [[Parti Plan]] | SKU-A için 500'lük parti aç — Stok/talep ile parti ve iş emri |
| [[Bu ay planı]] | [[Parti Plan]] | Bu ay planı — Stok/talep ile parti ve iş emri |
| [[Lot Barkod]] | [[Lot Barkod]] | Parti/lot kodu üretimi ve sevk bağlama |
| [[Lot L-2411 oluştur]] | [[Lot Barkod]] | Lot L-2411 oluştur — Parti/lot kodu üretimi ve sevk bağlama |
| [[Lot L-2411 nereye gitti]] | [[Lot Barkod]] | Lot L-2411 nereye gitti — Parti/lot kodu üretimi ve sevk bağlama |
| [[Min Max]] | [[Min Max]] | Yeniden üretim tetik noktası |
| [[Min altına düşenleri listele]] | [[Min Max]] | Min altına düşenleri listele — Yeniden üretim tetik noktası |
| [[Min 200 yap]] | [[Min Max]] | Min 200 yap — Yeniden üretim tetik noktası |

### Olmalı (0)

_Yok._

### İyi olur (4)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Verim Rapor]] | [[Verim Rapor]] | Plan vs üretilen vs fire. Çekirdek genişleme: Raporlar. |
| [[SKU-B verim raporu]] | [[Verim Rapor]] | SKU-B verim raporu — Plan vs üretilen vs fire. Çekirdek genişleme: Raporlar. |
| [[Alternatif Reçete]] | [[Alternatif Reçete]] | Malzeme yokluğunda alternatif BOM |
| [[Alternatif reçeteyi uygula]] | [[Alternatif Reçete]] | Alternatif reçeteyi uygula — Malzeme yokluğunda alternatif BOM |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[Mikro]]

## 7. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
