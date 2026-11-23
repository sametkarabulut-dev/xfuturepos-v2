---
tip: sektor
durum: taslak
---
# {{title}}

## Özet
- 

## Alt işletme türleri (onay listesi)
> İşaretli = onaylandı. ⚠️ = sınırda, kullanıcı kararı bekliyor (`onay-bekliyor`).

- [ ] 

## Sektörün ortak ihtiyaçları
- 

## Yasal çerçeve
- 

## Pazar büyüklüğü
| Gösterge | Değer | Kaynak |
|---|---|---|
|  |  |  |

## Bu sektördeki işletme türleri
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
formulas:
  oncelik: '((pazar_puani + odeme_puani + rekabet_puani + kolaylik_puani + aciliyet_puani) / 5).toFixed(1)'
properties:
  file.name:
    displayName: İşletme türü
  note.durum:
    displayName: Durum
  formula.oncelik:
    displayName: Öncelik
views:
  - type: table
    name: İşletme türleri
    order:
      - file.name
      - note.durum
      - formula.oncelik
    sort:
      - property: formula.oncelik
        direction: DESC
```

## Kaynaklar
- 
