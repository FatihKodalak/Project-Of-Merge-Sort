# Merge Sort Projesi

------

### Soru

**[16,21,11,8,12,22]** Dizisi için,

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

------

------

### Cevaplar

------

#### **1. Merge Sort**

```
                                                          [16,21,11,8,12,22]

                                                        [16,21,11]   [8,12,22]

                                                     [16,21]-[11]     [8, 12]-[22]

                                                  [16] [21] [11]       [8] [12] [22]

                                                     [11,16] [21]     [8,12] [22]

                                                        [11,16,21]   [8,12,22]

                                                          [8,11,12,16,21,22]


```

----

**2. Big-O Gösterimi**

* Big-O Gösterim Formülü = O(n log n)
  * O(6 log 6)



