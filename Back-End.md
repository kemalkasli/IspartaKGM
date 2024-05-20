### Back-End Tasarım Çalışmaları <br/>

Docker: Kullanılmadı. REST API: Kullanıldı.<br/>

ygulama Client ve Server olarak iki farklı kısım klasörde oluşturdum. Her iki klasörüde node_modules hariç iki ayrı repoya push işlemi yaptım.<br/>
[Server klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM2)<br/>
[Client klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM3)<br/>
Ayrıca iki klasörün node_modules klasörleri dahil şekilde sıkıştırıp github repo boyutunu aştığı için drive a yükledim. <br/>
[Uygulama drive linki](https://drive.google.com/drive/folders/1iEWgud2vp9ba-QpB4jMtH32ihJdgG4sB)<br/>



Kemal KAŞLI Backend Kodlama (Server Klasörü)<br/>


1-) Kritik Noktaların Listelenmesi                       Route: get("/",getAllPoints)       controllers\pointCOntroller.js     <br/>
2-) Kritik Noktaların Kontrol Kesime göre Listelenmesi (map)    <br/>
3-) Kritik Noktaların Ekleme                             Route:post("/",createPoint)           controllers\pointCOntroller.js <br/>
    Tek Kritik Nokta Çağır  (Update Delete için)         Route: get("/:id",getSinglePoint)     controllers\pointCOntroller.js<br/>
4-) Kritik Noktaların Güncelleme                         Route: put("/:id",updatePoint)        controllers\pointCOntroller.js <br/>
5-) Kritik Noktaların Silme                              Route: delete("/:id",deletePoint)     controllers\pointCOntroller.js <br/>
<br/>
<br/>
6-) Ticari Tesislerin Listesi                           Route: get("/",getAllConstructions)  controllers\ConstructionController.js     <br/>
7-) Ticari Tesislerin Kontrol Kesime Göre Listelenmesi (map)    <br/>
8-) Yeni Ticari Tesisin Eklenmesi                       Route:post("/",createConstruction)    controllers\ConstructionController.js <br/>
    Tek Ticari Tesis Çağır  (Update Delete için)        Route: ("/:id",getSingleConstruction) controllers\ConstructionController.js<br/>
9-) Ticari Tesislerin Bilgilerinin Güncellenmesi        Route: put("/:id",updateConstruction  controllers\ConstructionController.js <br/>
10-)Ticari Tesislerin Silinmesi                         Route: delete("/:id",deleteConstruction) controllers\ConstructionController.js<br/>






