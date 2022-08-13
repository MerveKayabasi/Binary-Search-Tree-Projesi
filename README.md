# Binary-Search-Tree-Projesi
SORU: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
      Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
     
      1. Aşama: Root 7'dir. Root'un sağında büyük değerler solunda küçük değerler bulunur. O nedenle 7'nin sağ tarafında ağacımızda 8 bulunur ve sol tarafında 5
                bulunur.
                                         7
                                        /  \ 
                                       5    8
                                            
                
       2. Aşama: 1 sayısı 7'den ve 5'ten küçük olduğu için 5'in soluna eklenir.
       
                                         7
                                        / \
                                       5   8
                                      /
                                     1
                                     
        3. Aşama: 3 sayısı hem 7'den hem 5'ten küçüktür fakat 3 sayısı 1'den büyükür. Bu nedenle 1'in sağ tarafına yazılır.
        
                                         7
                                        / \
                                       5   8
                                      /
                                     1
                                      \
                                       3
        
        4. Aşama: 6 sayısı 7'den küçük 5'ten büyük olduğu için 5'in sağ tarafına yazılır. 0 sayısı ise 7, 5 ve 1'den küçük olduğu için 1'in soluna yazılır.
                                        
                                        7
                                       / \
                                      5   8
                                     / \
                                    1   6
                                   / \
                                  0   3
                                  
          5. Aşama: 9 sayısı 7'den ve 8'den büyük olduğu için 8'in sağına yazılır. 4 sayısı 7 ve 5'ten küçük 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır. 2 sayısı ise 7 ve 5'ten küçük fakat 1'den büyüktür. Bu durumda 1'in sağına bakarız. 1'in sağında 3 var. 2, 3'ten küçük olduğu için 3'ün soluna yazılır. 
          
          
                                      7
                                     / \
                                    5    8
                                   / \    \
                                  1   6     9
                                 / \
                                0    3
                                    / \
                                   2    4
                                   
     www.patika.dev       
