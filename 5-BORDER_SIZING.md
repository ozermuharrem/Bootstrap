# BORDER & SIZING # 

Nesnelere border ekleyebilmek için class ın içerisine border yazdığımızda dört köşeden border ekler <br>
> **border-top üstten , border-end-> soldan , border-bottom -> alttan , border-start -> sağdan border tanımlayabiliriz** <br>
tüm köşeler değilde 3 köşeden border ekleyebilmek için border-0 denildiğinde dört köseden de borderleri siler<br>
boreder-top-0 -> üstten border çıkart , border-end-0 -> sağdan border çıkart , border-bottom-0 -> alttan border çıkart , border-start-0 soldan border çıkart anlamına gelir<br>
Örneğin border-top-0 sınıfı verildiğinde sağa, alta ve sola border uygular üst tara border uygulamaz<br>
Borderlere renk de verebiliriz border border-danger sınıfa uygulandığında border rengi kırmızı uygulanır diğer renkler için de geçerlidir<br> 

![image](https://user-images.githubusercontent.com/86782430/155860890-7d9ea612-fab4-44ca-b84c-57345da27aca.png)

**Çıktı**

![image](https://user-images.githubusercontent.com/86782430/155860908-9828814f-88d8-4835-9019-fb87af06cd16.png)

>**bordere dört köşesinden yuvarlatma yanı radius ekleyebilmek için "rounded" eklememiz gerekir.**<br>
**dört köşeden değil de istediğimiz köşlere radius eklemek için rounded-top -> üstteki köşelerde yuvarlatma , rounded-bottom -> alttaki köşelerde yuvarlatma yapar**
>**raunded-circle** yuvarlak bir daire içerisine alır <br>
>**rounded-pill** ise tam yuvarlak değil ortaları bıraz daha düz bir görüntü elde etmiş oluruz

![image](https://user-images.githubusercontent.com/86782430/155861023-d4c40038-4a6e-4a17-9d2e-11e1242d2e37.png)

**Çıktı**

![image](https://user-images.githubusercontent.com/86782430/155861040-85a71faa-0a33-4759-a10d-3de7a0dca325.png) 

>resimlerin köşelerini yuvarlatmak için de kullanılabilir img etiketinin class'ına eklendiği zaman<br>

Divlere withg ekleye bilmek için **w** karekterini kullanıyoruz<br>
>**tarayıcının w-25 -> withg %25 , w-50 -> withg %50 , w-75 -> witgh %75 , w-100 -> withg %100 alanını kaplayan divler oluşturabiliriz.**<br> 

![image](https://user-images.githubusercontent.com/86782430/155861307-58ec8f20-626f-4b36-afc3-dd9f364e5cfa.png)

**Çıktı**

![image](https://user-images.githubusercontent.com/86782430/155861315-48631de6-2a33-49f8-8dda-a64105b3a646.png)

>**height için ise "h" karekterini kullanıyoruz**<br>
**tarayıcının h-25 -> height %25 , h-50 -> height %50 , h-75 -> height %75 , h-100 -> height %100 alanını kaplayan divler oluşturabiliriz.**

![image](https://user-images.githubusercontent.com/86782430/155861533-c2ba25f5-b634-4136-b933-ca3a0fe240d3.png)

![image](https://user-images.githubusercontent.com/86782430/155861433-d9072568-c927-406b-aef8-498a54b14906.png)

**Çıktı**

![image](https://user-images.githubusercontent.com/86782430/155861447-33677fff-bd7f-49c7-bad2-046266cb6e93.png)

başlangıçta yükseklik içermediği için öncelikle height 400px atadık ve daha sonra divler blok eleman olduğundan dolayı yan yana durmaları için inline-block elemana çevirdik yukarıda ki görüntüyü yani yüksekliği anlayabilmek için<br>

>**divlere yada elemanlara gölgelendirme ekleye bilmek için sınıfa shadow yazmamız yeterli olacaktır**<br>
**shadow-sm -> small gölge , shadow-lg -> large gölge ekler**
