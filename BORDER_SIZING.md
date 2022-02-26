<h1> BORDER & SIZING </h1> 

<p> Nesnelere border ekleyebilmek için class ın içerisine border yazdığımızda dört köşeden border ekler </p>
<p> border-top üstten , border-left-> soldan , border-bottom -> alttan , border-right -> sağdan border tanımlayabiliriz </p> 
<p> tüm köşeler değilde 3 köşeden border ekleyebilmek için border-0 denildiğinde dört köseden de borderleri siler </p>
<p> boreder-top-0 -> üstten border çıkart , border-left-0 -> sağdan border çıkart , border-bottom-0 -> alttan border çıkart , border-right-0 soldan border çıkart anlamına gelir</p>
<p> Örneğin border-top-0 sınıfı verildiğinde sağa, alta ve sola border uygular üst tara border uygulamaz</p>
<p>Borderlere renk de verebiliriz border border-danger sınıfa uygulandığında border rengi kırmızı uygulanır diğer renkler için de geçerlidir</p> 
![image](https://user-images.githubusercontent.com/86782430/155860890-7d9ea612-fab4-44ca-b84c-57345da27aca.png)
<p> Çıktı</p>
![image](https://user-images.githubusercontent.com/86782430/155860908-9828814f-88d8-4835-9019-fb87af06cd16.png)

<p>bordere dört kçşesinden yuvarlatma yanı radius ekleyebilmek için "rounded" eklememiz gerekir.</p>
<p>dört köşeden değil de istediğimiz köşlere radius eklemek için rounded-top -> üstteki köşelerde yuvarlatma , rounded-bottom -> alttaki köşelerde yuvarlatma yapar</p>
![image](https://user-images.githubusercontent.com/86782430/155861023-d4c40038-4a6e-4a17-9d2e-11e1242d2e37.png)
<p> Çıktı</p>
![image](https://user-images.githubusercontent.com/86782430/155861040-85a71faa-0a33-4759-a10d-3de7a0dca325.png) 

<p> resimlerin köşelerini yuvarlatmak için de kullanılabilir img etiketinin class'ına eklendiği zaman </p> 

<p>Divlere withg ekleye bilmek için w karekterini kullanıyoruz </p>
<p>tarayıcının w-25 -> withg %25 , w-50 -> withg %50 , w-75 -> witgh %75 , w-100 -> withg %100 alanını kaplayan divler oluşturabiliriz. </p> 
![image](https://user-images.githubusercontent.com/86782430/155861307-58ec8f20-626f-4b36-afc3-dd9f364e5cfa.png)
<p> Çıktı</p>
![image](https://user-images.githubusercontent.com/86782430/155861315-48631de6-2a33-49f8-8dda-a64105b3a646.png)

<p>height için ise "h" karekterini kullanıyoruz </p>
<p>tarayıcının h-25 -> height %25 , h-50 -> height %50 , h-75 -> height %75 , h-100 -> height %100 alanını kaplayan divler oluşturabiliriz. </p> 
![image](https://user-images.githubusercontent.com/86782430/155861533-c2ba25f5-b634-4136-b933-ca3a0fe240d3.png)
![image](https://user-images.githubusercontent.com/86782430/155861433-d9072568-c927-406b-aef8-498a54b14906.png)
<p> Çıktı</p>
![image](https://user-images.githubusercontent.com/86782430/155861447-33677fff-bd7f-49c7-bad2-046266cb6e93.png)
<p>başlangıçta yükseklik içermediği için öncelikle height 400px atadık ve daha sonra divler blok eleman olduğundan dolayı yan yana durmaları için inline-block elemana çevirdik yukarıda ki görüntüyü yani yüksekliği anlayabilmek için </p> 

<p> divlere yada eemanlara gölgelendirme ekleye bilmek için sınıfa shadow yazmamız yeterli olacaktır</p>
<p> shadow-sm -> small gölge , shadow-lg -> large gölge ekler </p> 
