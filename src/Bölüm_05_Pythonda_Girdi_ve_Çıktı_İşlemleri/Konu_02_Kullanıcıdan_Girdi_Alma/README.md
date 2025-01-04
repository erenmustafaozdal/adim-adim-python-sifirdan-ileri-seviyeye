# Kullanıcıdan Girdi Alma

Kullanıcıdan veri almak, programlarımızı interaktif hale getiren önemli bir özelliktir. Python'da kullanıcıdan girdi almak için **`input()`** fonksiyonu kullanılır. Bu fonksiyon, kullanıcıdan bir veri girişi bekler ve kullanıcının klavye aracılığıyla verdiği değeri alır. Bu veri, varsayılan olarak her zaman bir **string (metin)** türündedir.

---

## `input()` Fonksiyonu Nedir?

Python'da **`input()`** fonksiyonu, kullanıcıdan bir veri alır ve bu veriyi bir string olarak döndürür. Kullanıcıdan alınan bu veri bir değişkene atanabilir.

### Kullanım Şekli:

```python
değişken = input("Kullanıcıya gösterilecek mesaj: ")
```

### Örnek:

```python
isim = input("Lütfen adınızı girin: ")
print("Merhaba", isim)
```

**Çıktı:**

```
Lütfen adınızı girin: Eren
Merhaba Eren
```

### Detaylar:

- **`input("...")` içindeki metin** kullanıcıya bir açıklama sağlar. Kullanıcı bu mesajı gördükten sonra klavye ile veri girişi yapabilir.
- Kullanıcının girdiği veri her zaman bir **string** türündedir.

---

### Özet

- **`input()`** fonksiyonu ile kullanıcıdan veri alınır ve bu veri string olarak döner.

Bu bilgilerle programlarını interaktif hale getirebilir ve kullanıcıdan dinamik girdiler alarak işlemler yapabilirsin.
