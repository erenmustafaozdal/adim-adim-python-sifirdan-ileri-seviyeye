# Python Kurulumu

Python, açık kaynaklı ve geniş bir topluluk tarafından desteklenen popüler bir programlama dilidir. Python’u bilgisayarınıza kurarak bu güçlü dili öğrenmeye başlayabilirsiniz. Aşağıda, hem Windows, macOS hem de Linux işletim sistemlerinde Python kurulumu adım adım açıklanmaktadır.

![Python web sitesi](/images/python.png)

## 1. Windows İçin Python Kurulumu

### Adım 1: Python Web Sitesinden Python İndir

1. Python’un resmi web sitesi olan [python.org](https://www.python.org/downloads/) adresine gidin.
2. Sayfanın üst kısmında, işletim sisteminize uygun olan Python sürümünü (en son sürüm önerilir) indirin.

### Adım 2: Python Yükleyicisini Çalıştırın

1. İndirdiğiniz dosyayı çalıştırın.
2. Kurulum ekranında **“Add Python to PATH”** seçeneğini işaretleyin. Bu adım, Python’un komut satırında çalıştırılabilmesi için gereklidir.
3. Ardından **“Install Now”** seçeneğine tıklayın.

### Adım 3: Kurulumu Doğrulayın

1. Python kurulduktan sonra, komut istemcisini (cmd) açın.
2. `python --version` veya `python -v` komutunu girerek kurulumun başarılı olup olmadığını kontrol edin.
   - Python sürümü görüntülenirse kurulum başarılı demektir.

### Adım 4: pip Paket Yöneticisini Doğrulayın

1. `pip --version` komutunu yazarak Python’un paket yöneticisi olan pip’in kurulu olduğunu doğrulayın.
2. Eğer pip yüklü değilse, Python kurulum dosyasını tekrar çalıştırarak **“Modify”** seçeneği üzerinden pip’i yükleyebilirsiniz.

## 2. macOS İçin Python Kurulumu

### Adım 1: Python Web Sitesinden Python İndir

1. [python.org](https://www.python.org/downloads/) adresinden macOS için en güncel Python sürümünü indirin.
2. İndirdiğiniz .pkg dosyasını açın ve yükleyici talimatlarını takip edin.

### Adım 2: Python’u Doğrulayın

1. Terminal uygulamasını açın.
2. `python3 --version` komutunu girin. Python’un doğru sürümünü görüntülüyorsanız kurulum başarılıdır.

### Adım 3: pip’i Doğrulayın

1. Python ile birlikte gelen pip’i kontrol etmek için terminalde `pip3 --version` komutunu çalıştırın.
2. pip yüklü değilse, `python3 -m ensurepip --upgrade` komutunu kullanarak pip’i yükleyebilirsiniz.

## 3. Linux İçin Python Kurulumu

Linux’te Python genellikle varsayılan olarak kurulu gelir. Ancak, en son sürümü yüklemek için aşağıdaki adımları izleyebilirsiniz.

### Adım 1: Python Paketini Yükleyin

Çoğu Linux dağıtımında Python paketlerini paket yöneticileri ile kolayca kurabilirsiniz.

- Debian/Ubuntu tabanlı sistemler için:
  ```bash
  sudo apt update
  sudo apt install python3
  ```
- Red Hat/CentOS tabanlı sistemler için:
  ```bash
  sudo yum install python3
  ```

### Adım 2: Python’u Doğrulayın

1. Terminal’i açın ve `python3 --version` komutunu girerek Python’un kurulu olup olmadığını kontrol edin.
2. Sürüm bilgisi görünüyorsa kurulum başarılıdır.

### Adım 3: pip’i Kurun

1. pip’in kurulu olup olmadığını kontrol etmek için `pip3 --version` komutunu çalıştırın.
2. Eğer kurulu değilse, aşağıdaki komutla pip’i yükleyebilirsiniz:
   ```bash
   sudo apt install python3-pip
   ```

## Ek Notlar:

- Python’un eski sürümleri de bulunabilir, ancak yeni başlayanlar için en son Python 3 sürümü önerilir. Python 2, artık resmi destek almamaktadır.
- PATH değişkenini doğru ayarladığınızdan emin olun, aksi takdirde komut satırından Python çalıştırılamayabilir.

Bu adımları takip ederek Python’u kurduktan sonra, programlama dünyasına ilk adımınızı atmış olacaksınız.
