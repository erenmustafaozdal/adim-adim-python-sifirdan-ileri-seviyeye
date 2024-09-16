# Çıktı Alma

Python'da bir programın sonuçlarını veya bilgilerini ekrana yazdırmak için kullanılan temel fonksiyon `print()` fonksiyonudur. Bu fonksiyon, yazılım dünyasında çıktıyı kullanıcıya göstermek amacıyla en çok kullanılan yöntemdir. Şimdi `print()` fonksiyonunun detaylarına inelim.

## Temel Kullanım

En basit haliyle, `print()` fonksiyonu içine verilen metni veya ifadeyi ekrana yazdırır:

```python
print("Merhaba Dünya!")
```

Bu kod çalıştırıldığında, çıktı:

```
Merhaba Dünya!
```

## Sayılar ve Aritmetik İşlemler

`print()` fonksiyonu, sayıları ve aritmetik işlemlerin sonuçlarını da yazdırabilir.

```python
sayi1 = 10
sayi2 = 20
print(sayi1 + sayi2)
```

Çıktı:

```
30
```

## Birden Fazla Argüman ile Kullanım

`print()` fonksiyonu birden fazla argümanı virgülle ayırarak ekrana yazdırabilir. Argümanlar arasında otomatik olarak bir boşluk eklenir.

```python
print("Merhaba", "Dünya", "!", 42)
```

Çıktı:

```
Merhaba Dünya ! 42
```

## `sep` ve `end` Parametreleri

`print()` fonksiyonunda varsayılan olarak argümanlar arasına bir boşluk koyulur. Ancak `sep` (separator) parametresi ile bu ayracı değiştirebiliriz:

```python
print("Python", "programlama", "dili", sep="-")
```

Çıktı:

```
Python-programlama-dili
```

`end` parametresi ise satırın sonunda eklenen varsayılan karakteri (yeni satır karakteri) değiştirmeye yarar:

```python
print("Merhaba", end=" ")
print("Dünya")
```

Çıktı:

```
Merhaba Dünya
```

## Dosyaya Yazdırma

Çıktıyı sadece ekrana değil, bir dosyaya da yazdırabilirsiniz:

```python
with open("çıktı.txt", "w") as dosya:
    print("Bu bir dosya yazdırma işlemidir.", file=dosya)
```

## Özet

Bu bölümde, Python'da `print()` fonksiyonu kullanarak çıktının nasıl alınacağını öğrendiniz. `print()` fonksiyonunun temel kullanımı, sayılarla birlikte kullanımı, birden fazla argüman ile kullanımı ve `sep`, `end` parametrelerinin kullanımını keşfettiniz. Artık çıktılarınızı daha etkili ve okunabilir bir şekilde ekrana yazdırabilirsiniz.
