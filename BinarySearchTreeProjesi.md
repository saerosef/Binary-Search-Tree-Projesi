# Patika.dev Binary Search Tree

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


````
1. Root 7'dir. 
2. 5, 7'den küçük olduğu için soluna yazılır. 
3. 1, 5'ten küçük olduğu için 5'in soluna yazılır. 
4. 8, 7'den büyük olduğu için 7'nin sağına yazılır. 
5. 3, 1'den büyük olduğu için 1'in sağına yazılır.
6. 6, 5'ten büyük olduğu için 5'in sağına yazılır.
7. 0, 1'den küçük olduğu için 1'in soluna yazılır.
8. 9, 8'den büyük olduğu için 8'in sağına yazılır. 
9. 4, 3'ten büyük olduğu için 3'ün sağına yazılır.
10. 2, 3'ten küçük olduğu için 3'ün soluna yazılır.
````


1. 7

2.         7
          /
         5

3.           7
            /
           5 
          /
         1 

4.           7
            / \
           5   8
          /
         1 

5.           7
            / \
           5   8
          /
         1
          \
           3

6.           7     
            / \
           5   8
          / \
         1  6
          \
           3  
       
7.             7     
              / \
             5   8
            / \   
           1   6   
          / \
         0   3 
     
8.           7     
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3 
      
9.           7     
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3 
            \
             4 
            
10.            7     
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3 
            / \
           2   4 
        




[patika.dev] https://www.patika.dev/
