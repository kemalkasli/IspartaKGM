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
Ayrıca iki klasörün node_modules klasörleri dahil şekilde sıkıştırıp github repo boyutunu aştığı için drive a yükledim. )<br/>
[5-> Uygulama drive linki ](https://drive.google.com/drive/folders/1iEWgud2vp9ba-QpB4jMtH32ihJdgG4sB)<br/>
5.1) Terminal ekranından cd komutuyla client klasörüne içine girilir.<br/>
5.2) Client klasörünün içirisinde iken npm start komutuyla node js başlatılır.<br/>
5.3) [eslint] Plugin "react" was conflicted between "package.json » eslint-config-react-app »
hatası alınır ise package.json dosyası açılıp ctrl+s ile kaydet işlemi yapılınca normal şekilde başlatılıyor.<br/>
5.4) Yeni Terminal ekranından cd komutuyla server klasörüne içine girilir.<br/>
5.5) Server klasörünün içirisinde iken npm start komutuyla node js başlatılır.<br/>
5.6) Tarayıcından http://localhost:3000/ ile ana sayfaya ulaşılır.<br/><br/>
Projeyi local de yukarıdaki şekilde çalıştırmayı başarabildim. Canlıya almak için aşağıdaki adımları izledim. <br/>
Vercel hesabı açıp her iki klasörü ayrı ayrı uzak sunucuya aktarmayı denedim.<br/>
[Server klasörünün vercel linki](https://ispartakgm2.vercel.app/)<br/>
[Client klasörünün vercel linki](https://ispartakgm.vercel.app/)<br/>
Bu şekilde çalıştıramayınca Netlify hesabı açık aynı şekilde yüklemeyi denedim.<br/>
[Server klasörünün netlify linki](https://thriving-kashata-b41564.netlify.app/)<br/>
[Client klasörünün netlify linki](https://ispartakgm.netlify.app/)<br/>
Her iki sitede de deploy aşamasında hatalar alıp yayınlayamadım.<br/>


