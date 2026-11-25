---
tip: isletme
kod: "13-05-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Gıda işleme]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 10
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
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
  - "[[Lot İzle]]"
  - "[[SKT Parti]]"
  - "[[Kayıt Onay]]"
  - "[[Soğuk Kayıt]]"
  - "[[Geri Çağır]]"
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
  - "[[Lot İzle]]"
  - "[[Lot G-90 nereye gitti]]"
  - "[[Bu satışın hammaddesi]]"
  - "[[SKT Parti]]"
  - "[[SKT'si 7 gün kalanlar]]"
  - "[[FEFO ile sevk]]"
  - "[[Kayıt Onay]]"
  - "[[Kayıt belgesi bitiş tarihi]]"
  - "[[Onay kapsamım ne]]"
  - "[[Soğuk Kayıt]]"
  - "[[Soğuk oda bugün kaydı]]"
  - "[[Geri Çağır]]"
  - "[[Lot G-90 geri çağır]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 4
parca_durum: tamamlandi
---
# 13-05-01 · Gıda işleme

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 4

## 1. Özet
Bozulabilir girdiyi reçete ve parti ile işleyip piyasaya gıda arz eden işletme. Lokanta burada değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 10
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Reçete
2. lot
3. son tüketim tarihi
4. verim
5. kayıt veya onay dosyası.

```mermaid
flowchart LR
  S1["Reçete"] --> S2
  S2["lot"] --> S3
  S3["son tüketim tarihi"] --> S4
  S4["verim"] --> S5
  S5["kayıt veya onay dosyası."]
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
| [[Lot İzle]] | [[Lot İzle]] | Girdi-üretim-satış one-up/one-down izlenebilirlik |
| [[Lot G-90 nereye gitti]] | [[Lot İzle]] | Lot G-90 nereye gitti — Girdi-üretim-satış one-up/one-down izlenebilirlik |
| [[Bu satışın hammaddesi]] | [[Lot İzle]] | Bu satışın hammaddesi — Girdi-üretim-satış one-up/one-down izlenebilirlik |
| [[SKT Parti]] | [[SKT Parti]] | SKT/TETT ve FEFO sevk |
| [[SKT'si 7 gün kalanlar]] | [[SKT Parti]] | SKT'si 7 gün kalanlar — SKT/TETT ve FEFO sevk |
| [[FEFO ile sevk]] | [[SKT Parti]] | FEFO ile sevk — SKT/TETT ve FEFO sevk |
| [[Kayıt Onay]] | [[Kayıt Onay]] | İşletme kayıt/onay belgesi hatırlatıcı; tam HACCP suite değil |
| [[Kayıt belgesi bitiş tarihi]] | [[Kayıt Onay]] | Kayıt belgesi bitiş tarihi — İşletme kayıt/onay belgesi hatırlatıcı; tam HACCP suite değil |
| [[Onay kapsamım ne]] | [[Kayıt Onay]] | Onay kapsamım ne — İşletme kayıt/onay belgesi hatırlatıcı; tam HACCP suite değil |

### Olmalı (0)

_Yok._

### İyi olur (4)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Soğuk Kayıt]] | [[Soğuk Kayıt]] | Basit sıcaklık/ölçüm günlüğü |
| [[Soğuk oda bugün kaydı]] | [[Soğuk Kayıt]] | Soğuk oda bugün kaydı — Basit sıcaklık/ölçüm günlüğü |
| [[Geri Çağır]] | [[Geri Çağır]] | Lot bazlı geri çağırma ve müşteri listesi. Çekirdek genişleme: CRM. |
| [[Lot G-90 geri çağır]] | [[Geri Çağır]] | Lot G-90 geri çağır — Lot bazlı geri çağırma ve müşteri listesi. Çekirdek genişleme: CRM. |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[Mikro]]

## 7. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
