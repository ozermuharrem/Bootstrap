"# Bootstrap" 
Bu alanda Bootstrap kütüpanesi ile ilgili derslerimi not alıp örnek kodları yükleyeceğim. 

*****Bootstrap*****

Sadık Hoca Der Ki 

<i> Html ve Css bilgimizi kullanarak tasarımlarımızı çok daha hızlı ve bir standart içinde geliştirebilmek için son zamanlarda Bootstrap kütüphanesine kayıtsız kalmak neredeyse imkansız hale geldi.

Bootstrap kütüphanesi içinde işimizi kolaylaştıracak bir çok yapı mevcut, bize kalan sadece bu yapıların nasıl kullanıldığını öğrenmek üstelik bu süreç inanın ki çok basit...

Derslere başlamadan önce belirtmek isterim ki ;

Boostrap kütüphanesi içindeki bazı araçlar az da olsa Javascript bilgisi gerektiriyor. Eğer bu gerekliliği yüzde olarak vermiş olsam %5 diyebilirim. Yani Bootstrap kütüphanesinin sadece %5 'inde Javascript bilmemiz gerekiyor. Dolayısıyla Bootstrap derslerini Javascript derslerinin önüne almak istedim. Peki neden mi ?

Çünkü Bootstrap ile tasarımlarımız kesinlikle boyut atlayacaktır. Kısa zamanda neler yapabileceğinizi görmek bize büyük motive sağlayacaktır. Onca Javascript dersinden sonra bu motivasyonu kazanmamız bence geç olurdu :) Bu yüzden lütfen neden Javascript bilmeden bunları gösterdiniz demeyin sadece bir kaç ders içinde ufak bir ezber diyebiliriz. Javascript öğrendikten sonra ezber ile mantığı yer değiştireceğiz.

** Bölüm özetini içeren pdf dosyasını ders altından indirebilirsiniz.

** Ayrıca size kolaylık sağlaması için öğrendiklerimizle alakalı yazılı dökümanlar hazırlamaktayım. Css bölümü ile alakalı dökümanlar için tıklayınız.

** Bölüm boyunca oluşturduğumuz çalışma dosyalarını son ders altından indirebilirsiniz. </i>

<hr>

<h1> Bootstrap Nedir </h1>

<p> resmi web sitesi <a href="https://getbootstrap.com/" target="_blank">getbootsrap.com</a> dır.<br>
  Bootsrap css ve js kütüphanesidir. <br>
  Belli css sınıfları oluşturulmuştur. Bu sınıfları kullanarak daha hızlı kod yazmamıza yardımcı olacak.<br>
  class ismi kullanarak bu css sınıfını bootsrap kütüpanesi ile etkin hale getirebiliriz.<br></p>
  
  <hr>
  <br><br><br>
  
  <h2> Bootstrap Kurulumu </h2>
  <ul>
    <li>Bootstrap kütüphanesini kullanabilmek için kütüphane içerisinde buluna css ve js kütüphanelerini html sayfasına ekliyoruz </li>
  <li> getbootstrap.com sitesine gidip css kütüphanesini kopyalayıp html sayfasında ki head etiketi içerisine yapıştırıyoruz. </li>
  <li> js kütüphane linkini <strong>body</strong> etiketinin bitiş tagının üzerine yapıştırıyoruz.</li>
  
  <hr> 
  <br><br><br>
  <h2>HEADING & TEXT </h2>
  
  <p>h1 den h6 ya kadar bootsrap kütüphanesini başlık etiketlerine vermiş olduğu kendine has özellikleri vardır.</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153955760-af95fbf9-18c0-44c2-a0d1-b7b46f0651ad.png) 
  
  <p> Çıktı </p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153955922-87c65306-e07a-4c45-b16d-ba8a77111750.png)



  <p>Diğer etiketler örnegin "p" etiketini class'ına h2 eklersek h2 bootsrap ın tasarladığı h2 görüntüsünde olacaktır.</p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153956050-e0080e63-1e03-47ed-9416-dcf5da252a99.png)
  
  <p> Çıktı </p> 
  
   ![image](https://user-images.githubusercontent.com/86782430/153955922-87c65306-e07a-4c45-b16d-ba8a77111750.png) 
  
  <p> text-muted </p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153956684-7be8911f-e359-4d5c-8aac-0145a81d92f3.png)

  <p> Çıktı </p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153956791-81ab0469-2d54-4919-bc3d-99cbdb16c2e7.png) 
  
  <p><bold> display-1,2,3,4</bold></p>
  
  <p> display yazı boyutları büyüktür ve 4 adettir. Genelde arka planı resim olan görseller üzerinde daha kullanılır</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153957174-3a6d371e-9093-46b8-87c5-d3784b3f670a.png)

  <p> Çıktı</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153957314-b4ef4c50-974e-4993-ba29-bece4e709cb0.png) 
  
  <p><bold>lead</bold></p>
  
  <p> lead bir yazı sitilidir </p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153957573-ecc2563b-5c7c-4c0e-bdb5-01f76bfd1e16.png)

  <p> Çıktı</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153957631-18913fbe-d1b2-4b10-b7d9-949557a4ac75.png) 
  
  <p>text-lowercase = büyük yazılar küçültür</p>
  <p>text-uppercase = küçük yazılar büyütür</p>
  <p>text-capitalized = yazıların ilk harfleri büyür</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153957992-1d45487a-e846-49ad-b77d-92946bd19b49.png)
  
  <p> Çıktı</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153958116-63e49d43-0511-4e39-898a-2c235cc801f6.png) 
  
  <p>font-weight-bold = kaılın yazı sitili</p>
  <p>font-weight-normal = normal yazı sitili</p>
  <p>font-weight-light = layt yazı sitili</p>
  <p>font-italic = italik yazı sitili</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153958417-ece63cba-098c-4621-a0c2-a6e41e1f3e01.png)
  <p> Çıktı</p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153958529-1e71fd7f-5fb7-42ce-9d9a-bc97161dceb5.png) 
  
  <hr>
  <br><br><br>
  
  <h2> RENKLER </h2> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959033-a18e8d16-ac5c-4efa-9c1f-5ef4d26168e4.png)

  <p><bold> Çıktı</bold></p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153959181-5644eaec-d36a-49bb-a595-6a0360ad5756.png)
  
  <p> Renk kodları her yerde kullanılabilir. Birbirine uyumlu ve web sitesinin daha güzel ve renklerde standartı yakalamamıza yardımcı olacaktır. </p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959575-df4e4a11-bed2-4d71-bbfd-26437d6c0996.png) 
  
   <p><bold> Çıktı</bold></p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959744-adbbce6e-b47d-459c-86f9-178b9d6afeb3.png)

  
  ![image](https://user-images.githubusercontent.com/86782430/153959639-7729feec-af32-447b-9eca-6af0ba361c78.png) 
  
   <p><bold> Çıktı</bold></p> 
  
 ![image](https://user-images.githubusercontent.com/86782430/153959802-57adaab9-5030-4178-bb66-4ae20aeaadd1.png) 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959874-47a09230-c080-45de-8a9a-b0a8a4c485cd.png) 
  
    <p><bold> Çıktı</bold></p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959956-98df1f4c-e180-4d83-8b48-7733c447853d.png) 
  
    <hr>
  <br><br><br>
  
  <h2> BUTON </h2> 



  



  
  

  


  

  


  
  
  

  
  

