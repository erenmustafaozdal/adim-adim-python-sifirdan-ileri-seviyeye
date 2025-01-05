# Veri Tiplerini Kontrol Etme (type() İşlevi)

Python'da bir değişkenin veya ifadenin türünü kontrol etmek, programın işleyişini anlamak ve hatalardan kaçınmak için oldukça önemlidir. Bunun için Python, dahili olarak `type()` adlı bir işlev sunar. Bu işlev, bir değişkenin veya değerin hangi veri tipine ait olduğunu belirler ve kullanıcının bu bilgiyi programlama sırasında değerlendirmesini sağlar.

## **type() İşlevi Nedir?**

`type()` işlevi, bir değerin türünü döndüren yerleşik bir Python işlevidir. Örneğin, bir sayının mı, bir metnin mi yoksa bir listenin mi işlendiğini anlamak için kullanılabilir.

## **Kullanımı**

`type()` işlevi şu şekilde kullanılır:

```python
type(değer)
```

Burada `değer`, türünü kontrol etmek istediğiniz değişken veya ifadedir. Bu işlevin çıktısı, kontrol edilen değerin türünü temsil eden bir Python sınıfı olacaktır.

## **Örnekler**

### 1. Temel Veri Tipleriyle Kullanım

```python
# Bir tamsayının türünü kontrol etme
sayi = 42
print(type(sayi))  # Çıktı: <class 'int'>

# Ondalık bir sayının türünü kontrol etme
ondalik = 3.14
print(type(ondalik))  # Çıktı: <class 'float'>

# Metin türünü kontrol etme
metin = "Merhaba, Dünya!"
print(type(metin))  # Çıktı: <class 'str'>

# Boolean türünü kontrol etme
mantiksal = True
print(type(mantiksal))  # Çıktı: <class 'bool'>
```

### 2. Karmaşık Veri Tipleriyle Kullanım

```python
# Liste türünü kontrol etme
liste = [1, 2, 3, 4]
print(type(liste))  # Çıktı: <class 'list'>

# Sözlük türünü kontrol etme
sozluk = {"ad": "Eren", "yas": 30}
print(type(sozluk))  # Çıktı: <class 'dict'>

# Demet türünü kontrol etme
demet = (10, 20, 30)
print(type(demet))  # Çıktı: <class 'tuple'>

# Küme türünü kontrol etme
kume = {1, 2, 3, 4}
print(type(kume))  # Çıktı: <class 'set'>
```

Bu bilgiler, programlama sırasında veri türlerini doğru şekilde anlamanıza ve kullanmanıza yardımcı olacaktır. `type()` işlevi, Python'un güçlü ve kullanıcı dostu bir araç olmasının temel nedenlerinden biridir.
