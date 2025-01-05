# Sayı Veri Tipleri (int, float)

Python'da sayılar, **sayı veri tipleri** olarak adlandırılan kategorilerde sınıflandırılır. Bu tipler, bir programlama dilinde sayılarla çalışırken temel taşları oluşturur. Aşağıda bu veri tipleri hakkında detaylı bilgiler ve örnekler bulunmaktadır.

---

## 1. Tamsayılar (int)

**int** veri tipi, tam sayıları ifade eder. Negatif veya pozitif tam sayılar, Python'da bu veri tipine dahildir. Python'da bir değişkene tamsayı atadığınızda, türü otomatik olarak `int` olarak belirlenir.

### Örnekler:

```python
# Pozitif bir tamsayı
sayi1 = 42
print("sayi1:", sayi1, "Türü:", type(sayi1))  # Çıktı: <class 'int'>

# Negatif bir tamsayı
sayi2 = -17
print("sayi2:", sayi2, "Türü:", type(sayi2))  # Çıktı: <class 'int'>

# Sıfır da bir tamsayıdır
sayi3 = 0
print("sayi3:", sayi3, "Türü:", type(sayi3))  # Çıktı: <class 'int'>
```

## 2. Ondalıklı Sayılar (float)

**float** veri tipi, ondalıklı sayıların temsil edilmesi için kullanılır. Bu tür, reel sayıları temsil eder ve ondalık bir noktaya sahiptir. Python’da bir sayının float olabilmesi için ondalıklı bir kısmı olması gerekir.

### Örnekler:

```python
# Pozitif bir ondalıklı sayı
ondalik1 = 3.14
print("ondalik1:", ondalik1, "Türü:", type(ondalik1))  # Çıktı: <class 'float'>

# Negatif bir ondalıklı sayı
ondalik2 = -2.71
print("ondalik2:", ondalik2, "Türü:", type(ondalik2))  # Çıktı: <class 'float'>

# Ondalık kısmı 0 olan bir float
ondalik3 = 5.0
print("ondalik3:", ondalik3, "Türü:", type(ondalik3))  # Çıktı: <class 'float'>
```

## 3. Farklı Veri Tiplerinin Özellikleri

### Önemli Notlar:

- `int` ve `float` arasında işlem yapıldığında sonuç **float** olur.
- `int` türündeki bir değer, ondalıklı bir değere dönüştürülmeden **float** ile işlenebilir.
- Sayılar arasında dönüştürme işlemleri, ileride detaylı olarak anlatılacaktır.

### Örnek:

```python
# int ve float arasındaki işlemler
sonuc = 5 + 3.2
print("sonuc:", sonuc, "Türü:", type(sonuc))  # Çıktı: <class 'float'>
```

## 4. type() İşlevi ile Tür Kontrolü

type() işlevi kullanılarak herhangi bir sayının veri tipi kolayca kontrol edilebilir.

### Örnek:

```python
# Tamsayı
print("42'nin türü:", type(42))  # Çıktı: <class 'int'>

# Ondalıklı sayı
print("3.14'ün türü:", type(3.14))  # Çıktı: <class 'float'>
```

## 7. Özet

- `int`, tam sayıları temsil eder.
- `float`, ondalıklı sayıları temsil eder.
- **type()** işlevi ile bir değişkenin veri tipini kontrol edebilirsiniz.

Bu konuyu pekiştirmek için kendi örneklerinizi oluşturarak farklı sayı veri tiplerini keşfedebilirsiniz!
