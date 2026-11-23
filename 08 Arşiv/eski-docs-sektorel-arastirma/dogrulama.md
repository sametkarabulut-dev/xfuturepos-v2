# Doğrulama kapanışı

`dogrulanmali: true` kalan modül yok. Bayrak, soru kapandığı için indirildi. Bu, her kurumun KOBİ yazılımına API açtığı anlamına gelmez. Notun ilk cümlesi sonucu söyler: ya uç dokümanda vardır ya da panel kaydı tutulur ve resmi işlem kurum ekranında kalır.

Ödeme, bağlayıcı sözleşme, resmi başvuru ve müşteriye giden mesaj onay olmadan çıkmaz.

## Dokümanı açılan ve ucu olanlar

| Modül | Uç | Kaynak |
| --- | --- | --- |
| 09.00.02 | Google Calendar API | https://developers.google.com/calendar/api/guides/overview |
| 12.00.03 | U-ETDS eşya SOAP | https://uetds.uab.gov.tr/teknik-dokuman |
| 12.04.01 | Google Routes API | https://developers.google.com/maps/documentation/routes |
| 12.04.03, 16.00.03 | WhatsApp Cloud API | https://developers.facebook.com/docs/whatsapp/cloud-api |
| 12.07.02, 12.07.04, 13.00.02, 13.00.04, 13.03.03, 13.04.05, 13.06.01 | Mikro reçete, stok, irsaliye, e-İrsaliye gönderim | https://apidocs.mikro.com.tr/apis |
| 15.01.05 | GitHub REST, GitLab `/api/v4` | https://docs.github.com/en/rest · https://docs.gitlab.com/ee/api/rest/ |
| 15.02.01–05 | Meta Marketing API ve Google Ads API | https://developers.facebook.com/docs/marketing-api/overview/ · https://developers.google.com/google-ads/api/docs/access-levels |
| 16.00.02 | iyzico | https://dev.iyzipay.com/ |

Google Ads üretimi Test ile açılmaz. Explorer, Basic ve Standard başvuru ister. Meta tarafında canlı hesap yazması da uygulama incelemesine bağlıdır. iyzico tahsilatı ve WhatsApp şablonu onay kuyruğundadır. Mikro e-İrsaliye gönderimi GİB’e Mikro hesabından gider. Logo ve Nebim reçete uçları bu dokümanda olmadığı için listeden çıktı.

## Sayfası açılan, üçüncü parti API’si olmayanlar

- TTBS: https://ttbs.gtb.gov.tr/
- Web Tapu: https://webtapu.tkgm.gov.tr/
- EİDS: https://eids.ticaret.gov.tr/
- sahibinden kurumsal aktarım: sözleşmeli, EİDS’e entegre ilancılık firması
- UYAP: https://www.uyap.gov.tr/
- SPL: https://www.spl.com.tr/
- ŞANTİYE-M: https://cbs.csb.gov.tr/santiye-m-yazilimi-113510
- SBM: https://www.sbm.org.tr/
- MSG bildirim formu: https://msg.org.tr/dagitim/konser-etkinlik-bildirimi
- Gıda işletme kayıt: https://www.turkiye.gov.tr/gida-tarbil-isletme-kayit-belgesi

Bu modüllerde panel dosyayı, tarihi ve taslağı tutar. Kurum ekranına yazma yok.

## Adresi bu turda açılmayanlar

İSG-KATİP 504 verdi. UYDS, TOBB TIR ve dijital takograf adresi 500 verdi. BKM ÖHVPS adresi 500 verdi. Hepsiemlak, Airbnb, Booking.com, salon yazılımları, Biletix, Passo, PDKS, filo, Ro-Ro ve belediye için seçilmiş bir uç yok. Bunlar da panel kaydına bağlandı. Resmi işlem ilgili ekranda kalır.
