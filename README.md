Proje 2

1- [16,21,11,8,12,22] Merge Sort'a göre sıralayınız
  İlk olarak sayıları yarıya bölüp iki gruba ayırırız. [16,21,11] ve [8,12,22]
  Daha sonra bu grupları da ikiye ayırırız. [16], [21,11], [8], [12,22] olarak gruplanır.
  Burdan sonra aynı grupta birden fazla olanlar tek kalıncaya dek bölünür. [16], [21], [11], [8], [12], [22]
  Bütün gruplar tekli kaldıktan sonra eski gruplarına küçükten büyüğe olacak şekilde sıralanarak gruplanır. [16], [11,21], [8], [12,22]
  16 ve 8 diğer ikli gruplara dahil olur, 16 ilk olarak gruptaki en küçük ve en büyük sayıo ile kıyaslanır. En küçük sayıdan büyük ve en büyük sayıdan küçük olduğu için ikisinin arasına dahil olur. 8'de bu aşamaları izler. [11,16,21], [8,12,22]
  En son olarak da bu iki grup birleşir. İki gruptaki en küçük sayı iki sayı karşılaştırılır ve bulunur(8) başa yazılır. Ardından birinci grubun en küçük sayısı ile ikinci grubun kalan en küçük sayısı karşılaştırılır. Bu şekilde sayılar bitene kadar karşılaştırılır ve bulunur. Sonuç ise [8,11,12,16,21,22] şeklinde olur.

2- O(nlogn) şeklinde gösterilir.