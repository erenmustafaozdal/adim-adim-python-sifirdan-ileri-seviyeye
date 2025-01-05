# Python'da Sözlükler (Dictionaries)

Sözlükler (**dictionaries**), Python'da anahtar-değer (**key-value**) çiftlerini depolamak için kullanılan bir veri yapısıdır. Sözlükler, sıralı olmayan ve değiştirilebilir bir veri tipidir. Her anahtar (key), bir değere (value) bağlanır ve bu çiftler bir arada saklanır. Sözlükler, birden fazla farklı veri tipindeki veriyi kolayca organize etmek için çok kullanışlıdır.

## **Sözlüklerin Özellikleri**

1. **Anahtarlar benzersizdir:** Aynı anahtar birden fazla kez kullanılamaz. Aynı anahtar tekrar tanımlanırsa, son tanımlanan değer geçerli olur.
2. **Değerler tekrarlanabilir:** Bir sözlükte aynı değer birden fazla kez bulunabilir.
3. **Anahtarlar değiştirilemez:** Bir sözlükte anahtarlar değiştirilemez.
4. **Sırasızdır:** Sözlükler Python 3.7'den itibaren sıralı görünse de sıralı olmadıkları varsayılır.

## **Sözlük Oluşturma**

Bir sözlük süslü parantez `{}` ile oluşturulur. Her bir anahtar ve değer arasında `:` kullanılır. Anahtar-değer çiftleri ise virgül `,` ile ayrılır.

```python
# Boş bir sözlük
bos_sozluk = {}

# Anahtar-değer çiftleri ile sözlük
ogrenci = {
    "isim": "Ahmet",
    "yas": 21,
    "ders": "Matematik",
    "ortalama": 85.5
}
print(ogrenci)
```

## **Sözlük Elemanlarına Erişim**

Sözlük elemanlarına anahtarlar kullanılarak erişilir.

```python
# Sözlük elemanlarına erişim
print(ogrenci["isim"])  # Çıktı: Ahmet
print(ogrenci["yas"])   # Çıktı: 21
```

> **Not:** Eğer bir anahtar sözlükte yoksa `KeyError` hatası alınır. İleride bu hatadan kaçınma yöntemlerini öğreneceğiz.

## **Sözlüğe Eleman Ekleme veya Güncelleme**

Bir sözlükteki mevcut bir anahtara yeni bir değer atayarak güncelleme yapabilirsiniz. Eğer anahtar sözlükte yoksa, bu anahtar ve değeri sözlüğe eklenir.

```python
# Eleman ekleme
ogrenci["cinsiyet"] = "Erkek"
print(ogrenci)

# Eleman güncelleme
ogrenci["yas"] = 22
print(ogrenci)
```

## **Sözlük Uzunluğu**

Bir sözlükteki anahtar-değer çiftlerinin sayısını öğrenmek için `len()` fonksiyonu kullanılır.

```python
ogrenci = {
    "isim": "Ahmet",
    "yas": 21,
    "ders": "Matematik"
}
print(len(ogrenci))  # Çıktı: 3
```

## **Örnek Kullanımlar**

1. **Telefon Rehberi**

```python
rehber = {
    "Ahmet": "05001234567",
    "Mehmet": "05559876543",
    "Ayşe": "05347654321"
}
print(rehber["Ahmet"])  # Çıktı: 05001234567
```

2. **Ürün Stok Durumu**

```python
stok = {
    "elma": 50,
    "armut": 30,
    "muz": 20
}
stok["elma"] = 35  # Elma stoğunu yenile
print(stok)  # Çıktı: {'elma': 35, 'armut': 30, 'muz': 20}
```

## **Sözlüklerin Kullanım Alanları**

- Verileri organize etmek ve kategorilere ayırmak.
- Rehber veya indeks oluşturma.
- Anahtar-değer ilişkisi ile çalışılan her türlü durumda.

Bu bilgilerle artık Python'da sözlüklerle nasıl çalışacağınızı temel düzeyde öğrenmiş oldunuz. Sözlüklerin daha ileri özelliklerini ilerleyen derslerde detaylıca ele alacağız.
