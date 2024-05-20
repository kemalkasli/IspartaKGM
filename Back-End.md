Docker: Kullanılmadı. REST API: Kullanıldı/Kullanılmadı.

ygulama Client ve Server olarak iki farklı kısım klasörde oluşturdum. Her iki klasörüde node_modules hariç iki ayrı repoya push işlemi yaptım.
[Server klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM2)
[Client klasörünün github repo linki] (https://github.com/kemalkasli/IspartaKGM3)
Ayrıca iki klasörün node_modules klasörleri dahil şekilde sıkıştırıp github repo boyutunu aştığı için drive a yükledim. 
[Uygulama drive linki](https://drive.google.com/drive/folders/1iEWgud2vp9ba-QpB4jMtH32ihJdgG4sB)



Kemal KAŞLI Backend Kodlama (Server Klasörü)


1-) Kritik Noktaların Listelenmesi                       Route: get("/",getAllPoints)       controllers\pointCOntroller.js     
2-) Kritik Noktaların Kontrol Kesime göre Listelenmesi (map)    
3-) Kritik Noktaların Ekleme                             Route:post("/",createPoint)           controllers\pointCOntroller.js 
    Tek Kritik Nokta Çağır  (Update Delete için)         Route: get("/:id",getSinglePoint)     controllers\pointCOntroller.js
4-) Kritik Noktaların Güncelleme                         Route: put("/:id",updatePoint)        controllers\pointCOntroller.js 
5-) Kritik Noktaların Silme                              Route: delete("/:id",deletePoint)     controllers\pointCOntroller.js 


6-) Ticari Tesislerin Listesi                           Route: get("/",getAllConstructions)  controllers\ConstructionController.js     
7-) Ticari Tesislerin Kontrol Kesime Göre Listelenmesi (map)    
8-) Yeni Ticari Tesisin Eklenmesi                       Route:post("/",createConstruction)    controllers\ConstructionController.js 
    Tek Ticari Tesis Çağır  (Update Delete için)        Route: ("/:id",getSingleConstruction) controllers\ConstructionController.js
9-) Ticari Tesislerin Bilgilerinin Güncellenmesi        Route: put("/:id",updateConstruction  controllers\ConstructionController.js 
10-)Ticari Tesislerin Silinmesi                         Route: delete("/:id",deleteConstruction) controllers\ConstructionController.js






