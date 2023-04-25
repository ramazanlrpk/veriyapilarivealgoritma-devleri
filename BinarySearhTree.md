Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisi Binary Search Tree aşamaları:

7 root olarak seçilir.
5, 1, 8, 3, 6, 0, 9, 4, 2 sırayla 7'nin alt düğümleri olarak eklenir.
5 7'nin sol düğümü olarak eklenir.
1 5'in sol düğümü olarak eklenir.
8 7'nin sağ düğümü olarak eklenir.
3 5'in sağ düğümü olarak eklenir.
6 3'ün sağ düğümü olarak eklenir.
0 1'in sol düğümü olarak eklenir.
9 8'in sağ düğümü olarak eklenir.
4 3'ün sol düğümü olarak eklenir.
2 1'in sağ düğümü olarak eklenir.
Bu aşamalardan sonra Binary Search Tree aşağıdaki gibi görünecektir
  
                7
               / \
              5   8
             / \   \
            1   3   9
           / \ / \
          0  2 4  6