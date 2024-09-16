# Python REPL ve Terminal Kullanımı

Python REPL (Read-Eval-Print Loop), Python'un etkileşimli bir çalışma ortamıdır. REPL sayesinde, Python kodlarını anında yazarak test edebilir ve sonuçlarını terminalde görebilirsiniz. Bu, programlama öğrenmeye yeni başlayanlar için oldukça faydalı bir araçtır, çünkü yazdığınız her satır kodun çıktısını anında görerek geri bildirim alırsınız.

Python REPL ve terminal kullanımını anlamak, Python ile etkili bir şekilde çalışmak için gereklidir. Şimdi bu kavramları detaylı bir şekilde ele alalım.

## Python REPL Nedir?

Python REPL, "Okuma, Değerlendirme, Yazdırma Döngüsü" anlamına gelir. Python yorumlayıcısının sağladığı bir komut satırı aracıdır. REPL, yazılan her Python ifadesini okur (Read), değerlendirir (Eval), sonucu yazdırır (Print) ve ardından bir sonraki komutu bekler (Loop).

REPL'i başlatmak için terminali açarak `python` veya `python3` komutunu çalıştırmanız yeterlidir. Örneğin:

```bash
$ python3
```

Bu komut çalıştırıldığında Python REPL başlar ve aşağıdaki gibi bir komut satırı görüntülenir:

```bash
Python 3.9.1 (default, Dec  8 2020, 07:51:42)
[GCC 9.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Bu `>>>` ifadesi Python REPL’in komut satırını temsil eder ve bu satırda Python kodlarınızı yazabilirsiniz. Örneğin:

```python
>>> print("Merhaba Dünya!")
Merhaba Dünya!
```

Bu kodu yazdıktan sonra REPL hemen sonucu gösterecektir.

## REPL'in Özellikleri

- **Hızlı Geri Bildirim**: Her bir Python kodunu anında çalıştırarak sonucunu görebilirsiniz.
- **Test Ortamı**: Küçük kod parçacıklarını test etmek için idealdir.
- **Deneme Yanılma**: Kodların nasıl çalıştığını öğrenmek ve hataları hızlıca tespit etmek için kullanılır.

## Terminal Kullanımı

Python programlarını terminal üzerinden çalıştırmak, REPL kullanmaktan biraz farklıdır. Terminal, yazdığınız Python dosyalarını çalıştırmak için kullanılır. Terminal üzerinden Python kodu çalıştırmak için şu adımları izleyebilirsiniz:

1. **Python Dosyası Oluşturma**: İlk olarak bir Python dosyası oluşturmanız gerekir. Örneğin, `hello.py` adında bir dosya oluşturun ve şu kodu yazın:

```python
print("Merhaba Dünya!")
```

2. **Terminalde Python Dosyası Çalıştırma**: Dosyanızı kaydettikten sonra terminali açın ve dosyanızın bulunduğu dizine gidin. Ardından şu komutu girin:

```bash
$ python3 hello.py
```

Bu komutu çalıştırdığınızda terminalde "Merhaba Dünya!" çıktısını göreceksiniz.

## REPL ile Terminal Arasındaki Farklar

- **REPL**: Satır satır Python kodu yazıp anında sonuç almanızı sağlar.
- **Terminal**: Daha büyük ve karmaşık Python programlarını dosya olarak kaydedip çalıştırmak için kullanılır.

## REPL ve Terminal Kullanımının Avantajları

- **REPL**: Hızlı denemeler ve hata ayıklamalar için mükemmeldir.
- **Terminal**: Programlarınızı kaydedip tekrar tekrar çalıştırmanıza olanak tanır.

Bu bilgiler, Python'da hem REPL hem de terminal kullanımı hakkında temel bir anlayış kazandıracak ve Python programlarınızı yazarken hangi araçları ne zaman kullanmanız gerektiğini öğreneceksiniz.
