<h1> MARGIN & PADDING </h1>

**margin** için "m" karekterini kullanıyoruz<br>
**padding** için "p" karekterini kullanıyoruz <br>
"div class ="m-2" div e uygulanan m-2 class'ı ile dört köşesinden de margin uygulamış oluruz.<br>
**margin ve padding için 0 dan başlayıp 5 e kadar değer atayabiliriz.** 
	<table>
	  <thead>
		<tr>
		  <td>
			  Köşeler
		  </td>
		  <td>
			 Açıklaması
		</td>
		</tr>
	  </thead>
	  <tbody>
		<tr>
		  <th>
			t
		  </th>
		  <th>
			top : üst köşe
		  </th>
		</tr>
		<tr>
		  <th>
			b
		  </th>
		  <th>
			bottom : alt köşe
		  </th>
		</tr>
		<tr>
		  <th>
			s
		</th>
		<th>
		  start left : sol köşe 
		</th>
	   </tr>
	   <tr>
		<th>
		  e
		 </th>
		<th>
		  end right : sağ köşe
		  </th>
		</tr>
	   <tr>
		<th>
		  x
		 </th>
		<th>
		  left right :sol ve sağ köşe
		  </th>
		</tr>
	   <tr>
		<th>
		  y
		 </th>
		<th>
		  top bottom : üst ve alt köşe
		  </th>
		</tr>
	  </tbody>  
	</table>

<table> 
  <tr>
    <td> m-0</td> <td> 0!important </td>
   </tr>
   <tr>
    <td> m-1</td> <td> 0.25rem!important </td>
   </tr>
   <tr>
    <td> m-2</td> <td> 0.50rem!important </td>
   </tr>
   <tr>
    <td> m-3</td> <td> 1rem!important </td>
   </tr>
   <tr>
    <td> m-4</td> <td> 1.5rem!important </td>
   </tr>
   <tr>
    <td> m-5</td> <td> 3rem!important </td>
   </tr>
</table>
<p> Yukarıda ki değerleri alır dört köşeden </p> 

![m-0](https://user-images.githubusercontent.com/86782430/155860045-5cc3ca4b-67f8-4b85-a017-4801c77b470a.png)

<p> Çıktı </p>

![image](https://user-images.githubusercontent.com/86782430/155860093-2c025ab0-cba7-450f-bf94-6c400d822c93.png)

<p> Dört köşeden değilde her bir alan için farklı değerler tanımlamak için yapmamaız gereken margin-right için -> me , margin-left için -> ms , margin-top için -> mt , margin-bottom için -> mb sınıfları verilir. Örneğin mb-3 sınıfını verdiğimizde margin-bottom dan 1 rem lik alan açar. </p>

<p>alttan ve üstten veya sağdan ve soldan değer atayabilmek için yatayda x değeri  ve dikeyde ise y değeri eklenir</p>

<p>margin-top, margin-bottom => my ve margin-left, margin-right => mx 0 ile 5 değeri arasında size eklenerek kullanılır. Örneğin mx-4</p>

<p> margin için uyguladığımız değerler padding için de geçerlidir </p> 


<p> padding için "p" karekterini kullanıyoruz</p>
<p>"div class ="p-2" div e uygulanan p-2 class'ı ile dört köşesinden de padding uygulamış oluruz. </p> 
<p> padding için de 0 dan başlayıp 5 e kadar değer atayabiliriz. </p> 
<table> 
  <tr>
    <td> p-0</td> <td> 0!important </td>
   </tr>
   <tr>
    <td> p-1</td> <td> 0.25rem!important </td>
   </tr>
   <tr>
    <td> p-2</td> <td> 0.50rem!important </td>
   </tr>
   <tr>
    <td> p-3</td> <td> 1rem!important </td>
   </tr>
   <tr>
    <td> p-4</td> <td> 1.5rem!important </td>
   </tr>
   <tr>
    <td> p-5</td> <td> 3rem!important </td>
   </tr>
</table>
<p> Yukarıda ki değerleri alır dört köşeden </p> 

<p> Dört köşeden değilde her bir alan için farklı değerler tanımlamak için yapmamaız gereken padding-right için -> pe , padding-left için -> ps , padding-top için -> pt , padding-bottom için -> pb sınıfları verilir. Örneğin pb-3 sınıfını verdiğimizde padding-bottom dan 1 rem lik alan açar. </p>

<p>alttan ve üstten veya sağdan ve soldan değer atayabilmek için yatayda x değeri  ve dikeyde ise y değeri eklenir</p>

<p>padding-top, padding-bottom => py ve padding-left, padding-right => px 0 ile 5 değeri arasında size eklenerek kullanılır. Örneğin px-4</p>

