### K-Means Algoritması :dizzy:
- Merkez noktanın kümeyi temsil etmesi ana fikrine dayalı bir metottur.

- Verileri belirlenen küme sayısına göre, her küme için belirlenen ortalama değer doğrultusunda kümelenmesi üzerine çalışılır. K-Means algoritması eldeki verileri k adet kümede ve kümelerin ortalamalarına göre kümelere ayırır. K küme sayısı kullanıcı tarafından verilir.

- Kısaca <b>n tane nesneyi -küme içi benzerlik maksimum, kümeler arası benzerlik minimum olacak şekilde- k tane kümeye böler.

- Başlangıç küme merkezlerinin seçimi k-means'in sonucunu önemli oranda etkiler. Başlangıç noktalarının belirlenmesinde çeşitli teknikler vardır. Bu tekniklerden bazıları :

1) k sayısı kadar rastgele veri seçilip küme merkezleri olarak atanır.
<br>2)Veriler rastgele k tane kümeye atanır ve küme ortalamaları alınarak başlangıç küme merkezleri belirlenir.
<br>3)En uç değerlere sahip veriler küme merkezleri olarak seçilir.
4)Veri setinin merkezine en yakın noktalar başlangıç noktaları olarak seçilir.

<img src="Iteration.jpg" title="kmeans kümeleme adimlari">

##### :white_check_mark: Avantajı:
- Uygulunabilirliği kolaydır ve büyük veri kümelerinde hızlı çalışabilir. Veri sayısı çok fazla olan hesaplamalarda, K-Means, küme sayısı küçük ise hesaplamaları, hiyerarşik kümelemeden daha hızlı yapar.

##### :negative_squared_cross_mark: Dezavantajı:

- K-Means algoritması k küme sayısını tespit edememektedir. Bu nedenle uygun k sayısını bulana kadar bir deneme yanılma süreci gerçekleşmektedir.
- Gürültü verilere duyarlıdır. Bu veriler de kümelere dahil edilir.
