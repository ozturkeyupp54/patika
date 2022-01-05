# patika
açıklama
16,21,11,8,12,22]

Satın alma sıralamasına göre aşamalarını ifade eder.

Adım 1 : [ 16,21,11,8,12,22 ]
Adım 2 : [ 16,21,11 ] - [ 8,12,22 ]
Adım 3 : [ 16,21 ] - [ 11 ] - [ 8, 12 ] - [ 22 ]
Adım 4 : [ 16 ] - [ 21 ] - [ 11 ] - [ 8 ] - [ 12 ] - [ 22 ]
Adım 5 Birleştirme : [ 16,21 ] - [ 8]- [11 ] - [ 12,22 ]
Adım 6 Birleştirme : [ 8,16,21 ] - [11,12,22 ]
Adım 7 Birleştirme : [ 8,11,12,16,21,22 ]
Big-O gösterimini.

O(logn)
