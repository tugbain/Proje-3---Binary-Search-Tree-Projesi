# Patika.dev - Veri Yapıları ve Algoritmalar
## Proje 3 - Binary-Search-Tree-Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap:

Dizinin en başındaki eleman root olarak seçilir. Bu dizideki root 7'dir. 

1. Adım: 5 elemanı, 7'den küçük olduğu için 7'nin soluna gelir.
2. Adım: 1 elemanı, 7'den küçük olduğu için 7'nin soluna gelir. Daha sonra 5 elemanından küçük olduğu için yeni bir bağ ile sol tarafa yerleştirilir.
3. Adım: 8 elemanı, 7'den büyük olduğu için 7'nin sağına geçer.
4. Adım: 3 elemanı, 7'den küçük olduğu için sola, 5 elemanından küçük olduğu için sola, 1'den ise büyük olduğu yeni bir bağ ile sağa gelir.
5. Adım: 6 elemanı, 7'den küçük olduğu sola, 5'den büyük olduğu için yeni bir bağ ile sağ tarafa geçer.
6. Adım: 0 elemanı, 7'den küçük olduğu için sola, sırasıyla 1'e kadar gelir. 1'den küçük olduğu için sol tarafa yerleştirilir.
7. Adım: 9 elemanı, 7'den büyük olduğu için sağa, 8'den büyük olduğu için sağına geçer.
8. Adım: 4 elemanı, 7'den küçük olduğu için sola gelerek 3 elemanının sağına gelir.
9. Adım: 2 elemanı, 7'den küçük olduğu için sola ve sırasıyla takip ederek 3 elemanının soluna yerleştirilir.

<img width="234" alt="Ekran görüntüsü 2022-09-01 034125" src="https://user-images.githubusercontent.com/111930812/187810568-8c574b8c-501f-4a07-b597-65cb9838e774.png">
