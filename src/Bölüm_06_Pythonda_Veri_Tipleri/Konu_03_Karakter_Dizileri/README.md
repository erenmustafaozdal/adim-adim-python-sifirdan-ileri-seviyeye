# Karakter Dizileri (str)

Karakter dizileri, bir ya da birden fazla karakterden oluşan metinleri temsil eden veri tipidir. Python'da karakter dizileri `str` (string) veri tipiyle tanımlanır. Hem tek tırnak (`' '`) hem de çift tırnak (`" "`) kullanarak oluşturulabilir. Ayrıca üç tırnak (`''' '''` veya `""" """`) kullanarak birden fazla satırlık karakter dizileri oluşturabilirsiniz.

Bu konu, Python'da karakter dizileriyle ilgili temel bilgileri, özelliklerini ve bu veri tipi üzerinde yapabileceğimiz işlemleri kapsar.

### **Bu Bölümde Öğrenecekleriniz:**

- Karakter dizilerinin temel tanımı ve nasıl oluşturulduğu.
- `type()` fonksiyonuyla bir veri tipinin `str` olduğunu kontrol etme.
- Karakter dizilerini birleştirme ve tekrarlama işlemleri.
- Çıktı alma işlemleri ve karakter dizisiyle ilgili temel örnekler.

## Karakter Dizileri Nasıl Oluşturulur?

Karakter dizileri Python'da şu yöntemlerle tanımlanabilir:

```python
# Tek tırnak ile karakter dizisi
metin1 = 'Merhaba Dünya!'
print(metin1)

# Çift tırnak ile karakter dizisi
metin2 = "Python harika bir dil."
print(metin2)

# Boş bir karakter dizisi
bos_metin = ""
print("Boş karakter dizisi:", bos_metin)

# Üç tırnak ile karakter dizisi (çok satırlı metin)
cok_satirli = """Bu birden fazla satırlı
bir karakter dizisidir.
Python'da üç tırnak kullanılarak yazılır."""
print(cok_satirli)
```

## Veri Tipini Kontrol Etme

`type()` fonksiyonunu kullanarak bir verinin `str` tipinde olup olmadığını kontrol edebiliriz:

```python
metin = "Bu bir karakter dizisidir."
print("Verinin tipi:", type(metin))  # Çıktı: <class 'str'>
```

## Karakter Dizilerini Birleştirme ve Tekrarlama

İki karakter dizisini birleştirmek için `+` operatörü, bir karakter dizisini tekrar etmek için `*` operatörü kullanılabilir:

```python
# Birleştirme
ad = "Eren"
soyad = "Yılmaz"
tam_isim = ad + " " + soyad
print("Tam İsim:", tam_isim)

# Tekrarlama
tekrar = "Python! " * 3
print("Tekrarlanan Dize:", tekrar)
```

### **Önemli Not:**

Bu aşamada henüz karakter dizisi yöntemleri (ör. `upper()`, `lower()`) veya dilimleme işlemleri işlenmediği için bu konuların örnekleri verilmemiştir. Bu konular ileri bölümlerde detaylıca ele alınacaktır.
