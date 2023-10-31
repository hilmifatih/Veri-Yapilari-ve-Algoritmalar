# Veri Yapıları ve Algoritmalar Projeleri
## Insertion Sort Projesi

[22,27,16,2,18,6] -> insertion sort
- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

----------------------------

step 1 -> [2,27,16,22,18,6] -> n

step 2 -> [2,6,16,22,18,27] -> (n-1)

step 3 -> [2,6,16,22,18,27] -> (n-2)            ==>>  Big-O -> n+(n-1)+....+(n-4) = (n*(n+1))/2 -> O(n**2)

step 4 -> [2,6,16,18,22,27] -> (n-3)

step 5 -> [2,6,16,18,22,27] -> (n-4)

Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması

-[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

step 1 -> [2,3,5,8,7,9,4,15,6]

step 2 -> [2,3,5,8,7,9,4,15,6]

step 3 -> [2,3,4,8,7,9,5,15,6]

step 4 -> [2,3,4,5,7,9,8,15,6]

****************

## Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Big-O gösterimini yazınız.

                    [16,21,11,8,12,22]
                [16,21,11]-------[8,12,22]
            [16]----[21,11]----[8]----[12,22]
        [16]----[21]----[11]----[8]----[12]----[22]
            [16,21]----[11]----[8,12]----[22]
                [11,16,21]----[8,12,22]
                    [8,11,12,16,21,22]

2**x = n -> x=log(n)  her adımda ayırma O(n) ==>> O(nlog(n))

---------------------
## Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

                  7
                 / \
                5   8
               / \   \
              1   6   9
             / \
            0   3
               / \
              2   4
                       
                        