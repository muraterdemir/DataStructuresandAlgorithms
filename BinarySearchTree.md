[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] - Binary-Search-Tree Aşamaları patika.dev

Root olarak 7 rakamını seçip en başa koyuyoruz.

İkinci rakam 5, 7'den (root) küçük olduğu için sol alt tarafa alalım.

Üçüncü rakam 1, 7'den (root) küçük ama solda alt node 5'ten de küçük olduğu için 5'in sol alt tarafında yer alıyor.

Dördüncü rakam 8, 7'den büyük olduğu için 7'nin (root) sağında yer alıyor.

Beşinci rakamımız 3, 7'den (root) küçük. Alt node 5'ten de küçük, soldan devam ediyoruz. Ama 3, 1'den büyük olduğu için 1'in sağında yer alıyor.

Altıncı rakamımız 6, 7'den (root) küçük. Bir alt nod 5'ten büyük olduğundan 5'in sağında yer alıyor.

Yedinci rakam 0, 7'den (root) küçük. Soldan devam ediyoruz, 5'ten küçük, devam ediyoruz, 1'den de küçük olduğundan 1'in soluna yerleştiriyoruz.

Sekizinci rakamımız 9, 7'den büyük olduğu için 7'nin (root) sağından devam ediyoruz. Alt node 8'den de büyük, o zaman 8'in sağında yer alıyor.

Dokuzuncu rakamımız 4, 7'den (root) küçük. Soldan devam ediyoruz, alt node 5'ten küçük,sola devam, 1'den büyük, sağa dönüyoruz, 3'ten büyük olduğundan 4 sağ alt node olarak yerini alıyor.

Son rakamımız 2, 7'den (root) küçük. Soldan devam ediyoruz, alt node 5'ten küçük,sola devam, 1'den büyük, sağa dönüyoruz, 3'ten küçük olduğundan 2 sol alt node olarak yerini alıyor.

Binary Search Tree son hali aşağıdaki gibidir.
![BinarySearchTree](https://user-images.githubusercontent.com/48916488/209673562-836bc648-d1dc-4e1f-9ce2-5de573a09e8c.jpg)
