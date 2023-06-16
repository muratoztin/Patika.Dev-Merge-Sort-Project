# Patika.Dev-Merge-Sort-Project
![image](https://github.com/muratoztin/Patika.Dev-Merge-Sort-Project/assets/111575893/20027d02-e3f0-4c33-9f67-9a7fb87e4909)

Bölme : Öncelikle dizi en küçük parçalara kadar bölünür. Her seferinde ikiye bölerek bu işlemi gerçekleştiririz.
### 	[16, 21, 11, 8, 12, 22] --> [[16, 21, 11], [8, 12, 22]]
### 	[[16,21,11], [8, 12, 22]] --> [[[16], [21, 11]], [[8], [12, 22]]]
### 	[[[16], [21, 11]], [[8], [12, 22]]] -> [[[[16]], [[21], [11]]], [[[8]], [[12],[22]]]]
Birleştirme: Sonrasında parçaları sıralı biçimde birleştirerek sonuca varırız.
### 	[[[[16]], [[21], [11]]], [[[8]], [[12], [22]]]]      [[[16], [11, 21]], [[8], [12, 22]]]
### 	[[[16], [11, 21]], [[8], [12, 22]]] 		 	[[11, 16, 21], [8, 12, 22]]
### 	[[11, 16, 21], [8, 12, 22]] 				 [8, 11, 12, 16, 21, 22]
###   [8, 11, 12, 16, 21, 22]
Big-O gösterimi --> Her defasında ikiye bölerek ilerlediğimiz için 2x=n kez hesap yaparız. Ve her seferinde n kadar okuma yaparız.
### x=log2n	
### Big-O gösterimi = O(n.logn)
