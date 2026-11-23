---
tip: modul
kod: "12.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: opsiyonel
---
# U-ETDS Köprüsü

> Kod `12.00.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için.

## Özellikler
### MVP
- 34 ABC 123 seferini U-ETDS için hazırla
- Bugün bildirilmemiş seferleri göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sefer durumu yüklendi. İşlem: yeniSefer/yük alanlarını doldur, eksikleri işaretle. Çıktı: onaylı gönderim kuyruğu.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)

## Mevzuat
- KTY md.40 f.6; Resmi Gazete 15.05.2025. P1/P2 ve salt TİO eşya U-ETDS listesinde yok. Resmi teknik doküman V3.6 ile API varlığı doğrulandı.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

## Kullanan işletme türleri
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan işletme türleri
```
