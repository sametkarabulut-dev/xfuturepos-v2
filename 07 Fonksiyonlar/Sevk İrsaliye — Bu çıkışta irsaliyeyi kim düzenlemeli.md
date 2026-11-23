---
tip: fonksiyon
kod: "12.07.04-1"
arac: "[[Sevk İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu çıkışta irsaliyeyi kim düzenlemeli

> Kod `12.07.04-1` · Araç: [[Sevk İrsaliye]]

## Ne yapar
- Bu çıkışta irsaliyeyi kim düzenlemeli
- Bağlı modül: Mal çıkışında sevk/e-irsaliye yükümlüsünü (mal sahibi vs lojistik merkez) ayırt eden checklist.

## Kullanan alt dallar
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan alt dallar
```
