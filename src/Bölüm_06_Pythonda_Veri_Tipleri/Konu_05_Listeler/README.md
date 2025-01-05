# Python'da Listeler

**Liste**, birden fazla değeri bir arada tutmamızı sağlayan bir veri yapısıdır. Listeler, Python'da **sıralı** ve **değiştirilebilir** bir veri tipidir. Ayrıca, listeler birden fazla veri tipini içinde barındırabilir.

## Liste Oluşturma

Python'da liste oluşturmak için köşeli parantez `[]` kullanılır ve elemanlar arasında virgül `,` konur.

```python
# Boş bir liste
bos_liste = []

# Tek tip elemanlardan oluşan bir liste
sayilar = [1, 2, 3, 4, 5]

# Farklı veri tiplerini içeren bir liste
karisik_liste = [42, "Python", True, 3.14]

print("Boş liste:", bos_liste)
print("Sayılar listesi:", sayilar)
print("Karışık liste:", karisik_liste)
```

## Liste Elemanlarına Erişim

Liste elemanlarına **indeks** numarasıyla erişilir. Python'da indeksleme **0'dan başlar**.

```python
meyveler = ["elma", "armut", "çilek"]

# İlk eleman
print("İlk eleman:", meyveler[0])

# İkinci eleman
print("İkinci eleman:", meyveler[1])

# Son eleman
print("Son eleman:", meyveler[-1])
```

## Liste Elemanlarını Güncelleme

Bir liste elemanını güncellemek için indeks kullanılır.

```python
rakamlar = [0, 1, 2, 3, 4]

# 2. indeksteki elemanı güncelle
rakamlar[2] = 99

print("Güncellenmiş liste:", rakamlar)
```

## Liste Uzunluğunu Bulma

Bir listenin uzunluğunu bulmak için `len()` fonksiyonu kullanılır.

```python
sepet = ["elma", "armut", "muz"]
print("Liste uzunluğu:", len(sepet))
```

## Listelerin Özellikleri

1. **Sıralıdır**: Elemanların sırası korunur.
2. **Değiştirilebilir**: Liste üzerinde güncelleme yapılabilir.
3. **Çoklu veri tipleri**: Aynı liste içinde farklı veri tipleri bulunabilir.

### Sonuç

Listeler, Python'da veri saklama ve yönetme işlemleri için çok güçlü bir yapıdır. Bir sonraki derslerde listelerle ilgili daha ileri seviye işlemleri ve diğer veri yapılarını inceleyeceğiz.
