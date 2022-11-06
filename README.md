# BinarySearchTreeProjesi
Binary Search Tree Projesi

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root 7dir ve Binary Search Tree'yi buna göre kuracağım.

Sıra Sıra 7'nin yanındaka kalanları ağaca ekliyorum

---------------------------------------------------

7

7, 5ten büyük olduğu için ağacın sol tarafına yerleştirilmesi gerekir

                7 
  
             /
 
          5 
          
Daha sonra 1 gelir ve 7den küçük olduğu için sola geçer ve 5le de karşılaştırıldığında ondan da küçük olduğundan onun da soluna yazılır ve böylelikle ağacın kökünden küçük olanlar soluna, ağacın kökünden büyük olanlar ise sağına olacak şekilde kalan semboller yerleştirilir

                           7 
  
                       /      \
 
                    5           8
          
                 /     \           \
       
              1          6            9
         
            /    \
             
          0        3
          
                /    \
  
              2        4 
 
 
