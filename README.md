# IMDB-Sitesinden-Veri-ekme
  Bu projede amacım IMDB sitesinde en iyi 250 filmin içerisinden istediğim kadarını terminalde yazdırmak.  
  Bu projeyi yazabilmek için öncelikle requests ve BeautifulSoup kütüphaneleri indirmek gerekir.  
  ![image](https://user-images.githubusercontent.com/103186397/173689259-4e783432-6a05-4f38-90b1-c66b2898fb78.png)  
  *1. ve 2. Satırda indirdiğimiz kütüphaneleri import ediyoruz.    
  *3. Satırda ulaşmak istediğim en iyi 250 film sayfasına ulaşırız.  
  *4. Satırda sitenin html kodlarının içeriğine ulaşırız.  
  *5. Satırda html içeriği 2. Satırda import edilen kütüphaneyi kullanırız.  
  *6. Satırda soup.find ile html içeriğinde filmler ile ilgili bölgeye erişiriz.(limit=50 demek 250 filmden kaç tanesini seçeceğimizi belirler.)  
  *7. Satırda bir sayaç oluşturulur.  
  *8. Satırda liste içerisinde dönen bir döngü oluşturulur.  
  *9. Satırda html kodlarından alınan bilgiler ile filmin adı alınır.  
  *10. Satırda html kodlarından alınan bilgiler ile filmin yayınlandığı yıl bilgisi alınır.  
  *11. Satırda html kodlarından alınan bilgiler ile filme verilen puan bilgisi alınır.  
  *12. Satırda sayaç döngü her döndüğünde 1 artar.  
  *13. Satırda 9,10 ve 11. Satırda alınan bilgiler f string şekilde yazdırılır.  
  #### Örnek çıktı aşağıda olacak.  
  ![image](https://user-images.githubusercontent.com/103186397/173689446-665909a0-18c5-4ce5-9f69-abdc2000ddec.png)  
