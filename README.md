# patikadev---Merge-Sort
[16,21,11,8,12,22] -> Merge Sort
dizinin sort türüne göre aşamalarını yazınız.
						[16,21,11,8,12,22]

				[16,21,11] 				[8,12,22]
	[16]	[21,11]									[8]	[12,22]
[16]	[21]	[11]											[8]	[12]	[22]
	[16,21]  [11]									    [8]  [12,22]
			[11,16,21]						[8,12,22]
						 [8,11,12,16,21,22]

2. Big-O gösterimini yazınız.
sürekli kendini çağırarıp diziyi hep ikiye böler bölünen dizinin merge işlemi dizi uzunluğu olduğu için n işlem yapılır O(nlogn) olarak ifade edilir dizi 6 elemanlı olduğu için o(6log6)’dır.
