[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

              [16,21,11]   [8,12,22]

            [16,21] [11]  [8,12] [22]

        [16]   [21]   [11]     [8]   [12]   [22]

      [16,21]   [11]             [8,12]   [22]
        
         [11,16,21]                [8,12,22] 
           
                 [8,11,12,16,21,22]
                 
2. Big-O gösterimini yazınız.
    n    tane sayıda      2^0 (n-1) tane karşılaştırma oluyor.
n/2  n/2 tane sayıda      2^1 (n/2-1) tane karşılaştırma oluyor.
      .                                 .
      .                                 .
      .                                 .
      .                                 .
Bunu formül haline getirirsek:    ∑ 2^i [(n/2^i)-1] haline geliyor.
