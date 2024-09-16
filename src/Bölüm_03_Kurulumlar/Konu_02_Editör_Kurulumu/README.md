# Editör Kurulumu (VS Code)

Bu bölümde, Python ile kod geliştirmek için kullanabileceğiniz popüler ve güçlü bir editör olan **Visual Studio Code (VS Code)** kurulumunu ve temel yapılandırmalarını öğreneceksiniz. VS Code, kullanıcı dostu arayüzü, geniş eklenti desteği ve hafif yapısıyla Python geliştiricileri arasında yaygın olarak kullanılan bir kod editörüdür.

## Visual Studio Code Nedir?

**Visual Studio Code**, Microsoft tarafından geliştirilen ve hem amatör hem de profesyonel geliştiriciler için güçlü özellikler sunan açık kaynaklı bir kod düzenleyicisidir. Farklı diller için geniş bir desteğe sahip olan VS Code, özellikle Python gibi dillerde yazılım geliştirmeyi oldukça kolaylaştıran çeşitli araçlar ve uzantılar sunar.

### Özellikleri:

- **Çapraz platform desteği**: VS Code, Windows, macOS ve Linux'ta çalışır.
- **Eklentiler ve uzantılar**: Python, JavaScript, HTML, CSS gibi birçok dili destekleyen geniş bir eklenti ve uzantı mağazası bulunur.
- **Yerleşik terminal**: Hızlı bir şekilde komut satırına erişim sağlar.
- **Git entegrasyonu**: Versiyon kontrol sistemi Git ile kolayca entegre olur.
- **Debaj (Debugging)**: Kapsamlı hata ayıklama araçlarıyla kodunuzu kolayca test edebilirsiniz.

## VS Code Nasıl Kurulur?

### Adım 1: VS Code İndirme

![VS Code web sistes](/images/vscode.png)

- Öncelikle [VS Code’un resmi web sitesine](https://code.visualstudio.com/) gidin.
- İşletim sisteminize uygun olan sürümü seçin (Windows, macOS veya Linux).
- Dosyayı indirdikten sonra, kurulum dosyasını çalıştırın.

### Adım 2: Kurulum

1. İndirdiğiniz dosyayı açarak kurulum sihirbazını başlatın.
2. Lisans sözleşmesini kabul edin ve “İleri” tuşuna basın.
3. Kurulum yerini seçin (varsayılan bırakabilirsiniz).
4. "Add to PATH" seçeneğini işaretleyin (bu, VS Code'u terminal veya komut satırından çalıştırmanızı sağlar).
5. Gerekli diğer seçenekleri işaretleyip "Install" butonuna tıklayın.
6. Kurulum tamamlandıktan sonra "Finish" diyerek VS Code'u başlatabilirsiniz.

### Adım 3: Python Uzantısının Yüklenmesi

VS Code, Python ile kod geliştirebilmeniz için Python uzantısını yüklemenizi gerektirir. Uzantıyı yüklemek için şu adımları takip edin:

1. VS Code'u açın.
2. Sol taraftaki "Uzantılar" simgesine tıklayın veya `Ctrl+Shift+X` kısayolunu kullanın.
3. "Python" yazıp aratın.
4. Microsoft tarafından geliştirilen Python uzantısını seçin ve "Yükle" butonuna tıklayın.

Bu uzantı, Python kodlarınızı yazarken çeşitli işlevler sağlar:

- **Otomatik tamamlama (IntelliSense)**,
- **Hata ayıklama (Debugging)**,
- **Kod parçacıkları (Code Snippets)**,
- **Linting** gibi özellikleri etkinleştirir.

### Adım 4: Python Yürütülebilir Yolunun Ayarlanması

Python uzantısını yükledikten sonra, Python’un doğru çalışabilmesi için Python yürütülebilir yolunun VS Code'da ayarlanmış olması gerekir.

1. `Ctrl+Shift+P` tuş kombinasyonunu kullanarak Komut Paleti'ni açın.
2. “Python: Select Interpreter” komutunu arayın ve seçin.
3. Python’un kurulu olduğu sürümü listeden seçin. (Python 3.x.x gibi)

## 3. VS Code Kullanımı ve Yapılandırmalar

### VSCode Penceresi ve Temel Bileşenleri

#### Kullanıcı Arayüzü

- **Explorer**: Proje dosyalarınıza erişim sağlar.
- **Search**: Dosyalarınız içinde arama yapmanızı sağlar.
- **Source Control**: Versiyon kontrol sistemi ile entegrasyon sağlar.
- **Run and Debug**: Programlarınızı çalıştırma ve hata ayıklama özelliği sunar.
- **Extensions**: VSCode'un işlevselliğini artıran eklentileri yükleyebilirsiniz.

![VS Code kullanıcı arayüzü](/images/vscode%20screen.png)

### Temel Python Dosyası Oluşturma

1. VS Code’da yeni bir Python dosyası oluşturmak için `File` > `New File` seçeneğine tıklayın.
2. Dosyayı `.py` uzantısı ile kaydedin. Örneğin: `hello_world.py`.
3. Aşağıdaki gibi basit bir Python kodu yazın:
   ```python
   print("Merhaba, Dünya!")
   ```
4. Dosyanızı kaydedin ve çalıştırmak için terminalden veya VS Code içindeki "Çalıştır" (Run) butonuna tıklayın.

### Terminal Kullanımı

VS Code'da terminali açmak için `Ctrl+`` tuş kombinasyonunu kullanabilirsiniz. Buradan doğrudan komut satırına erişip Python dosyalarınızı çalıştırabilir veya diğer komutları girebilirsiniz.

### Eklentiler ve Uzantılar

VS Code, Python dışında birçok dili ve teknolojiyi destekleyen eklentilere sahiptir. Örneğin:

- **Pylint**: Python kodunuza stil kontrolü ve hata tespiti yapar.
- **Jupyter**: Python’da Jupyter Notebook kullanmak için gereklidir.
- **Prettier**: Kodunuzu formatlamak ve düzenlemek için kullanışlı bir araçtır.

## 4. Sonuç

Bu bölümde, Python ile yazılım geliştirmek için kullanabileceğiniz güçlü bir editör olan VS Code'un kurulumunu ve yapılandırılmasını öğrendiniz. Şimdi, Python programlamaya başlamak için uygun bir ortamınız var. İlerleyen bölümlerde, bu araçlarla daha gelişmiş kodlama tekniklerini öğrenecek ve projelerinizi geliştirmeye devam edeceksiniz.
