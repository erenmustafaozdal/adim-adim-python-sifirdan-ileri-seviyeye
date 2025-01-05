# Boolean Veri Tipi

Python'da **Boolean (bool)** veri tipi, yalnızca iki değere sahiptir: **True** (doğru) ve **False** (yanlış). Boolean veri tipi, programlarda koşullu ifadeleri değerlendirmek, karar vermek ve mantıksal işlemleri gerçekleştirmek için kullanılır.

## Boolean Değerleri

Python'da **True** ve **False** özel anahtar kelimelerdir. Büyük harfle başlamaları gerektiğine dikkat edin. Küçük harflerle yazılan `true` veya `false` ifadeleri hata verecektir.

```python
# Boolean değerler
doğru = True
yanlış = False

print("Doğru:", doğru)
print("Yanlış:", yanlış)
```

## type() ile Boolean Türünü Kontrol Etme

Bir değerin boolean olup olmadığını **type()** fonksiyonunu kullanarak kontrol edebilirsiniz.

```python
# Boolean türünü kontrol etme
print("Türü kontrol et (True):", type(True))
print("Türü kontrol et (False):", type(False))
```

## Boolean ve Sayılar

Boolean değerler, sayı sistemiyle bağlantılıdır. Python'da:

- **True** sayısal olarak `1`'e eşittir.
- **False** sayısal olarak `0`'a eşittir.

```python
# Boolean ve sayılar
print("True'nin sayısal değeri:", int(True))
print("False'nin sayısal değeri:", int(False))
```

Boolean değerler ile matematiksel işlemler yapılabilir.

```python
# Boolean ile matematiksel işlemler
sonuç = True + False
print("True + False =", sonuç)
```

## Boolean Değerlerin Kullanım Alanları

Boolean veri tipi programların çeşitli alanlarında kullanılır. Bu alanlar henüz işlenmedi. Detaylı bilgi ileride verilecek.

1. **Koşullu ifadelerde (if/else) karar verme.**
2. **Döngülerde koşul kontrolü.**
3. **Fonksiyonlardan mantıksal sonuç döndürme.**

## Özet

- **Boolean (bool)** veri tipi, yalnızca **True** ve **False** değerlerini alır.
- Karşılaştırma ve mantıksal işlemler sonucunda boolean değerler elde edilir. (Detaylı bilgi ileride verilecek.)
- Matematiksel işlemlerde **True = 1**, **False = 0** olarak değerlendirilir.
- Boolean değerler programlarda karar mekanizmalarının temelini oluşturur.

Bu konuyu iyi anlamak, ilerleyen derslerde koşullu ifadeler ve döngüleri öğrenirken işinize çok yarayacak!
