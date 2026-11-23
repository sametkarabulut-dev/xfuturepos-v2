# Adım 2 — Sektörel modül araştırması INDEX

Kaynak yalnız markdown. Önce [`ai-kaynak/00-tum-sektorler-ortak.md`](ai-kaynak/00-tum-sektorler-ortak.md), sonra sektör dosyası. Entegrasyon notu: [`dogrulama.md`](dogrulama.md). Liste: [`ai-kaynak/OKU.md`](ai-kaynak/OKU.md).

10, 13 ve 16 aynı alanlara çekildi: `oncelik` yalnız `MVP` veya `V2`, `durum` yalnız `zorunlu` veya `opsiyonel`. Eski `sonra` / `ileri` kayıtları V2 ve opsiyonel oldu. 16’da önceliği orta olan modül opsiyonel kaldı; hepsi hâlâ MVP sınırında.

Doğrulama kapanışı: `dogrulanmali: true` kalan modül yok. Ayrıntı [`dogrulama.md`](dogrulama.md).

## Kapanış kararları

1. EİDS ofis API’si sitede yok. Panel yetki dosyasını tutar. İlan doğrulaması platformda kalır.
2. Aidat ve icra UYAP’a yazılmaz. Kayıt ve ihtar taslağı panelde, başvuru onayla.
3. Değerleme banka entegrasyonu yok. Lisans tarihi ve Web Tapu paketi elle.
4. Kısa kiralama kimlik kaydı panelde. Kolluk bildirimi tesis ekranında.
5. Komisyon tutarı öneridir. e-Fatura çekirdek modüldedir, kesim onayla.
6. ŞANTİYE-M ve UYDS için üçüncü parti API yok. Paket panelde, kurum girişi kullanıcıda.
7. Puantaj ilk sürümde mobil yoklamadır. PDKS markası seçilmedi.
8. Bayi e-İrsaliye’si Mikro `EIrsaliyeGonderV2` ile, onayla gider. Ham GİB ucu yok.
9. Metraj serbest miktardır. ÇŞB poz kataloğu içeri alınmadı.
10. U-ETDS köprüsü yetki belgesi seçilince açılır. Belgesiz kiracıda kapalı başlar.
11. 12.04 şehir içi kuryedir. Tarifeli M1/M2 kargo aynı alt sektörde değil.
12. Fulfillment stok hareketi Mikro API. Pazaryeri seçilmedi.
13. Filo konumu elle veya CSV. Marka seçilmedi.
14. TİO ve G acentesi aynı alt sektörde, belge alanı ayrı.
15. ERP yolu Mikro REST. Logo ve Nebim listeden çıktı.
16. 13.03 ve 13.06 aynı firmada iki profil olarak durur.
17. 13.05 MVP’de kayıt, lot ve son tüketim tarihi var. Sensör ve geri çağırma V2.
18. Proje reçetesi iç panelde. Müşteri portalı yok.
19. Meta ve Google Ads dokümanı açık. Üretim yazması Explorer/Basic başvurusu ve onay ister.
20. 15.03 örtülü reklam listesi varsayılan açılmaz. Reklam üreten iş 15.02’dedir.
21. 15.07 lisans tarihi elle. 5651 yükümlülüğü barındıran iş için not olarak durur, ayrı modül açılmadı.
22. Kapora iyzico ile alınabilir. Çağrı onay olmadan gitmez.
23. Çok salon, seans kaydının yeri olarak durur. Ayrı alt sektör yok.
24. MSG eser listesi taslaktır. Gönderim formla, kullanıcıda.
25. Biletix ve Passo bağlanmadı. Hasılat elle.
26. 16.01 kendi mutfağında yemek çıkarıyorsa gıda kaydı o işletmenin notudur. Başka salona üretim 16.06’dadır.

## Özet tablo

| ID | Sektör | is_modeli | Ortak MVP | Alt sektör | Toplam modül | Toplam MVP | Dosya |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 09 | Emlak & Gayrimenkul | `karma` | 5/7 | 5 | 33 | 20 | [`09-emlak-gayrimenkul.md`](ai-kaynak/09-emlak-gayrimenkul.md) |
| 10 | İnşaat & Yapı | `karma` | 5/7 | 7 | 42 | 26 | [`10-insaat-yapi.md`](ai-kaynak/10-insaat-yapi.md) |
| 12 | Lojistik & Taşımacılık | `sevkiyat` | 5/7 | 7 | 42 | 26 | [`12-lojistik-tasimacilik.md`](ai-kaynak/12-lojistik-tasimacilik.md) |
| 13 | Üretim & İmalat | `uretim` | 5/5 | 6 | 35 | 23 | [`13-uretim-imalat.md`](ai-kaynak/13-uretim-imalat.md) |
| 15 | Teknoloji, Medya & Ajans | `karma` | 5/7 | 8 | 45 | 29 | [`15-teknoloji-medya-ajans.md`](ai-kaynak/15-teknoloji-medya-ajans.md) |
| 16 | Etkinlik & Organizasyon | `etkinlik` | 5/5 | 6 | 23 | 23 | [`16-etkinlik-organizasyon.md`](ai-kaynak/16-etkinlik-organizasyon.md) |
