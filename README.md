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
  
  <h2> RENKLER </h2> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959033-a18e8d16-ac5c-4efa-9c1f-5ef4d26168e4.png)

  <p><bold> Çıktı</bold></p>
  
  ![image](https://user-images.githubusercontent.com/86782430/153959181-5644eaec-d36a-49bb-a595-6a0360ad5756.png)
  
  <p> Renk kodları her yerde kullanılabilir. Birbirine uyumlu ve web sitesinin daha güzel ve renklerde standartı yakalamamıza yardımcı olacaktır. </p> 
  
  ![image](https://user-images.githubusercontent.com/86782430/153959575-df4e4a11-bed2-4d71-bbfd-26437d6c0996.png) 
  
   <p><bold> Çıktı </bold></p> 
  
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
  
  btn = class ına btn etklenirse o etiket artık buton olarak algılanır bootsrap kütüphanesi tarafından 
  
  Bir önce ki bölümde görmüş olduğumuz tüm renkler de butonlar için de kullanılmaktadır. 
  
  ![image](https://user-images.githubusercontent.com/86782430/153960769-42237ea3-dd5e-44a1-a71c-87ccbc183647.png)
  
  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153960845-c177b586-7b90-4f6c-bd24-c6e6ad0eee3f.png)

  btn btn-outline-danger 
  
  ![image](https://user-images.githubusercontent.com/86782430/153961073-4e2716c7-d1a6-41c4-b898-340aeb559730.png)

  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153961207-e69b8d2f-5143-4363-87a8-e13f5ce54e1d.png)
  
  maus hover olduğu zaman yazı karekter rengi ile arka plan rengi değişir 
  
  btn-lg, btn-sm, btn-block 
  ![image](https://user-images.githubusercontent.com/86782430/153961489-e31305fa-e23b-478d-bbef-03c1fc96a0c3.png)
  
  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153961410-c6660df7-f47e-4178-ac6f-e52ba00e7031.png) 
  
  btn-active : aktif edilmiş, üzerine tıklanmış bir buton görüntüsü verir 
  disabled attribute : tıklanamayan buton
  
  ![image](https://user-images.githubusercontent.com/86782430/153961727-d0945a87-55e1-4e21-b696-361b31f7441c.png)

  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153961804-519eb8db-2b7c-4811-a869-3247df4747b7.png) 
  
  btn-group : btonları yan yana gruplamak için kullanılır örneğin sayfanın alt kısmında bulunan sayfa numaraları gibi 
  
  btn-group-vertical : butonları alt alta gruplamak için kullanılır. 
  
  Not : Her iki bootsrap kodunu da bir div etiketinin class ına yazmamız gerekmektedir.
  
  ![image](https://user-images.githubusercontent.com/86782430/153962421-61207f7d-c204-4e49-9586-526f389bdfad.png)
  
  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153962305-c8387153-61d7-40f5-99b3-1ebd29a02f7d.png)

  ![image](https://user-images.githubusercontent.com/86782430/153962506-8327a3d3-c455-4900-8474-7bde78159d21.png)

  Çıktı 
  
  ![image](https://user-images.githubusercontent.com/86782430/153962338-da95a64b-96e8-4d04-b588-c3fd6d9b8b91.png)
  
  <p></p>
