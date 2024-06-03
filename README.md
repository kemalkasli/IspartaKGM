# IspartaKGM
Ispartaya bağlı devlet ve il yol yollarını tanıtan(21 adet kontrol  kesim yolu için) ve yol bağlantısındaki önemli noktalar ile  yine yol üzerindeki  ilçe belde köy kavşaklarını listeleyen tanıtıcı bir web sayfası 
<br/><br/>
[1-> Yazılım Gereksinim Analizi](https://github.com/kemalkasli/IspartaKGM/blob/main/Yaz%C4%B1l%C4%B1m%20Gereksinim%20Analizi%20-%202221032073%20-%20Kemal%20KA%C5%9ELI%20(08.03.2024).pdf)
<br/><br/>
[2-> Kullanım Senaryosu](https://github.com/kemalkasli/IspartaKGM/blob/main/Kullan%C4%B1m%20Senaryosu.pdf)
<br/><br/>
[3-> Kullanıcı Senaryosu Diyagramı (pdf)](https://github.com/kemalkasli/IspartaKGM/blob/main/Kullan%C4%B1c%C4%B1%20Senaryosu%20Diyagram%C4%B1.pdf)
<br/><br/>
![3-> Kullanıcı Senaryosu Diyagramı (jpeg)](https://github.com/kemalkasli/IspartaKGM/blob/main/Kullan%C4%B1c%C4%B1%20Senaryosu%20Diyagram%C4%B1.jpg)
<br/><br/>
[4-> Veri Tabanı Şeması (xml)](https://github.com/kemalkasli/IspartaKGM/blob/main/veri%20taban%C4%B1%20diyagram%C4%B1%20nosqldbm-19_03_2024_16_18_32.xml)
<br/><br/>
![4-> Veri Tabanı Şeması (png)](https://github.com/kemalkasli/IspartaKGM/blob/main/Veri%20Taban%C4%B1%20Diyagram%C4%B1.png)
<br/><br/>
## VİZE SONRASI ÇALIŞMALAR <br/><br/>
Tasarım Sayfası Kullanılan FrontEnd Çatısı = React JS (MERN)
Uygulama Client ve Server olarak iki farklı kısım klasörde oluşturdum.  Her iki klasörüde node_modules hariç iki ayrı repoya push işlemi yaptım. <br/>
[Server klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM2)<br/>
[Client klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM3)<br/>

### 5-) Local de Çalışması <br/>
Ayrıca iki klasörün node_modules klasörleri dahil şekilde sıkıştırıp github repo boyutunu aştığı için drive a yükledim. )<br/>
[Uygulamanın drive linki ](https://drive.google.com/drive/folders/1iEWgud2vp9ba-QpB4jMtH32ihJdgG4sB)<br/>
A-) Terminal ekranından cd komutuyla client klasörüne içine girilir.<br/>
B-) Client klasörünün içirisinde iken npm start komutuyla node js başlatılır.<br/>
C-) [eslint] Plugin "react" was conflicted between "package.json » eslint-config-react-app »
hatası alınır ise package.json dosyası açılıp ctrl+s ile kaydet işlemi yapılınca normal şekilde başlatılıyor.<br/>
D-) Yeni Terminal ekranından cd komutuyla server klasörüne içine girilir.<br/>
E-) Server klasörünün içirisinde iken npm start komutuyla node js başlatılır.<br/>
F-) Tarayıcından http://localhost:3000/ ile ana sayfaya ulaşılır.<br/><br/>

Ayrıca Uygulamayı tekrar lokalde çalışacak şekilde php ve sqllite kullanarak yeniledim. <br/>
Bu aşamanın da dosyaları github repo boyutundan fazla olduğu için drive yükledim. <br/>
[php +sqllite Uygulamanın drive linki](https://drive.google.com/drive/folders/1OUjiFWOUrhmDzEm3WpqhiSFULniW_HgG)<br/>
A-) Sıkıştırılmış klasörü çıkardım (UwAmp)<br/>
B-) UwAmp.exe dosyasını çalıştırınca  php sunucu çalışıyor.<br/>
C-) Tarayıcıdan http://localhost/ ile anasayfaya ulaşabiliyoruz..<br/>
D-) Anasayfadan devlet ve il yollarından istediğimize göre linke ulaşabiliyoruz. [örnek link](http://localhost/32006.php).<br/>
E-) Yine anasayfadan  Yol boyu tesisler listesine ve etüt raporlarına  ulaşabiliyoruz  [örnek link](http://localhost/tesisler.php).<br/>


### 6-) Front-End Tasarımı <br/>
Uygulama Client ve Server olarak iki farklı kısım klasörde oluşturdum.  Her iki klasörüde node_modules hariç iki ayrı repoya push işlemi yaptım. <br/>
[Server klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM2)<br/>
[Client klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM3)<br/>

[Front-End.md Dosyası](https://github.com/kemalkasli/IspartaKGM/blob/main/Front-End.md)<br/>

### 7-) Back-End Tasarımı <br/>
[Back-End.md Dosyası](https://github.com/kemalkasli/IspartaKGM/blob/main/Back-End.md)<br/>

Front End ve Back End tasarımlarını localde çalıştırdıktan sonra yayınlamak için Render.com  alan adını kullandım. <br/>
Bu aşamada da Backend kısmı için IspartaKGMServer frontEnd kısmı içinde Ispartakgm  isimli iki adet web service kullandım. <br/>
[Render.com Dashboard Sayfası](https://github.com/kemalkasli/IspartaKGM/blob/main/render.com.dashboard.jpg)<br/>

### 8-) Kontrol ve Test <br/>
[Test.md Dosyası](https://github.com/kemalkasli/IspartaKGM/blob/main/Test.md)<br/>

### 9-) Geliştirici ve Kullanıcı Dokümantasyonları<br/>
[Geliştirici ve Kullanıcı Dökümanları](https://app.gitbook.com/o/5dpfVM0tm9jja7OJJMMF/s/wICRG8ZgP9xj8oQr1tpe/)<br/>



Uygulama Adresi: [https://ispartakgm.onrender.com](https://ispartakgm.onrender.com/)<br/>
### Not: <br/>
Hocam projeyi yayınladıktan sonra unit testler de göründüğü gibi çalıştığını tespit etttim<br/>
Ancak farklı zamanlarda sayfayı denediğimde bazen normal görüntülerken  bazen de 503 bad gateway hatasını almaktayım.<br/>
Render.com dan free domain kullanmamdan kaynaklı veya yoğunluk kaynaklı olduğunu düşünüyorum.<br/>
Kolaylıklar diliyorum. 
<br/>













