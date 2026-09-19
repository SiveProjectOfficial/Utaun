[🇹🇷 Dil seçimine dön](./README.md)
# Utaun Nedir?  
  
Utaun, yalnızca cansız bileşik sinüzoidal modelleme (CSM ses sentezi) kullanarak UTAU için CV (Sessiz-Sesli) ses bankaları oluşturan bir Windows yazılımıdır.  
Belgeler klasörünüzde otomatik ses bankası ZIP arşivi oluşturulmasını ve çeşitli UTAU uyumlu yazılımlara doğrudan dışa aktarımı destekler.  

# Özellikler  

* Çalıştırıldığında Belgeler klasörünüzde otomatik olarak bir ses bankası ZIP dosyası oluşturur veya uyumlu yazılımlara doğrudan dışa aktarır.  
* Yalnızca cansız bileşik sinüzoidal modelleme (CSM ses sentezi) aracılığıyla sesli harfleri (A, I, U, E, O, N) üretir.  
* CV ses bankaları oluşturmak için Belgeler dizininizde yer alan ünsüz ve sesli ses klasörlerini yapılandırın.  
* Program içinde m, n, y ve w satırlarını otomatik olarak oluşturur.  
* Hiragana takma adları + İngilizce Romaji takma adlarını destekler (tüm telaffuzlar Japoncadır).  
* `oto.ini`, `character.txt` ve `readme.txt` dosyalarını otomatik olarak oluşturur.  
* PNG görünümlerini eşzamanlı olarak JPG ve BMP formatlarına dönüştürür (Not: `character.txt` için JPG kullanılır).  
* `readme.txt` ve `character.txt` kodlaması **Shift-JIS (ANSI)** ve **UTF-8** arasından seçilebilir (Not: UTF-8, OpenUTAU ve diğerleri ile uyumluluk sağlar).  
* Temel frekansı (ses tonunu) değiştirmeyi sağlar.  
* Özgürce özelleştirilebilir ses bankası adı (karakter adı).  
* **Açık ve Koyu modları destekler.**  
* **Dışa aktarım hedefinin seçilmesine izin verir.**  

# Kullanım Amacı  

* Cansız veya yapay sesler kullanarak UTAU ses bankaları oluşturmak istediğinizde.  
* Kendi sesinizle kayıt yapmayı zor veya rahatsız buluyorsanız ses bankası üretimi için.  
* Bileşik sinüzoidal modellemeye (CSM ses sentezi) dayalı ses materyallerinin araştırılması.  
* Özelleştirilmiş ses bankası prototiplemesi.  
* İnsan tarafından simüle edilmiş vocaloid varlıkları olarak doğrudan kullanmak üzere oluşturulan ZIP dosyasını açmak.  
* Video remixleri için ses materyali olarak kullanım (örn. OtoMAD, YTPMV).  

# Utaun Nasıl Kullanılır  

① Utaun'un en son sürümünü **[GitHub Releases](#Releases)** adresinden indirin.  
② ZIP klasör sürümünü indiriyorsanız, **"Consonant/Voiced Sound" klasörlerini ve `oto.ini` dosyasını doğrudan "Belgeler" klasörünüzün içine yerleştirin (OneDrive Belgeleri de desteklenir).** (Not: Yükleyici sürümünü kullanırsanız bunlar otomatik olarak yerleştirilir).  
③ `Utaun.exe` dosyasını seçtiğiniz herhangi bir klasöre yerleştirin.  
④ `Utaun.exe` dosyasını başlatın ve ses bankanızı oluşturmak için ekrandaki talimatları izleyin.  
⑤ Veri kaydetme hedefi olarak ZIP çıktısı (Belgeler vb.) veya UTAU ve OpenUTAU için doğrudan klasör dışa aktarımı arasından seçim yapabilirsiniz.  
*Not: Otomatik güncelleme özelliği gelecekteki sürümlerde sunulacaktır.*  

### Arayüz (UI) Görseli  
![Test Image 3](IMG_4239.jpeg)  

# Uyumluluk ve Oluşturulan Ses Bankalarının Kullanımı  

* **UTAU**  
  Uygulamanın içinden sıkıştırılmamış bir ses bankası klasörü olarak doğrudan `voice` klasörünüze aktarın ve hemen kullanın.  
* **OpenUTAU**  
  Uygulamanın içinden sıkıştırılmamış bir ses bankası klasörü olarak doğrudan `Singers` klasörünüze aktarın ve hemen kullanın.  
* **UtauTTS**  
  Dışa aktarılan ZIP dosyasını çıkartın ve `utauTTS` programının `voice` klasörüne yerleştirin.  
* **UtauV**  
  ZIP dosyasını çalışan UtaunV uygulama penceresine sürükleyip bırakın.  
* **UTAlet (Web Sürümü)**  
  ZIP dosyasını resmi web sitesi ekranına sürükleyip bırakın.  
*Not: Her bir yazılım veya web ortamındaki özel kullanım talimatları için lütfen ilgili yardım dosyalarına, kılavuzlara veya resmi belgelere başvurun.*  

# Sistem Gereksinimleri  

* Windows 10 ila 11 (64-bit / 32-bit desteği)  
**(Not: Dosya boyutu hususları nedeniyle temel olarak 32-bit sürüm kullanılır, ancak program 64-bit Windows üzerinde de sorunsuz çalışır.)**  

# Desteklenmeyen Özellikler  

* Sesli ünlü harfler (あ゙, い゙, ゔ, え゙, お゙)  
* Fısıltılar, nefesler veya üfleme bileşenleri gibi ifade edici varyasyonlar  
* Palatalize sesler (örn.: kya, kyu, kyo / sha, shu, sho)  
* VCV (Sürekli Ünlüler)  
* CVVC  
* Diğer özel telaffuzlar  

# Kullanım Koşulları  

Utaun uygulamasının (`Utaun.exe`) kendisiyle ilgili aşağıdaki eylemler kesinlikle yasaktır:  
* Değiştirme  
* Düzenleme  
* Tadilat  
* Ticari kullanım  
* Yeniden dağıtım  
* Derlemeden çıkarma (disassembly)  

# Oluşturulan İçerik  

(Ses bankaları, `.wav` dosyaları, `icon.jpg` / `icon.bmp`, `oto.ini` vb.)  
Oluşturulan içerikler için kendi kullanım koşullarınızı belirlemekte (dağıtıcı olarak siz) özgürsünüz.  
Lütfen tercih ettiğiniz lisans koşullarını `readme.txt` içine yazın.  

Güncelleme bilgileri ve detaylar için lütfen GitHub üzerindeki **Releases** sayfasını kontrol edin.  

# Releases  
[Download Turkish Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇹🇷)
