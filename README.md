# BinarySearchTree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Çözümler
İlk önce array sıralanır. --> [0,1,2,3,4,5,6,7,8,9]

Root 4 kabul edilir, ve 4'ten küçük değerler için sola, büyük değerler için sağa bakılır.
Eğer bakılan yerde herhangi bir node yoksa o node oraya eklenir varsa aynı işlem o node için de yapılır.
