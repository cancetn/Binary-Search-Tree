
# Binary Search Tree

## Patika.dev egitim kampi süresince yapilmis proje odevdir.

[7,5,1,8,3,6,0,9,4,2] -> Binary Search Tree

Dizi 7 elemani ile baslamaktadir. Root=7;



                      7
                     / \
                    5   8
                   /\    \ 
                  1  6    9
                 /\
                0  3
                   /\
                  2  4

* Root=x, Root'un sagi=y ve Root'un solu=z olarak dusunuldugunde; 
* Root=7 için x=7 varsayilmis olur
* Dizinin 1. index numarali elemani '5'. 5<7 oldugu icin 5=z olarak Root'un soluna yazılır.
* Dizinin 2. index numarali elemani '1'. 1<7 oldugu icin Root'un soluna dogru yolculugu baslar. Ardından 5 ile karsilastirilir. 1<5 oldugu icin 5'in soluna yazilir.
* Dizinin 3. index numarali elemani '8'. 8>7 oldugu icin ve Root degerinin saginde bir deger olmadigi icin dogrudan Root degerinin sagina yazilir.
* Dizinin 4. index numarali elemani '3'. 3<7 oldugu icin Root degerinin soluna dogru yolculugu baslar. Ardindan 3<5 oldugu icin 5'in solundan yolculuguna devam eder. 3>1 oldugu icin 1 sayisinin sagina yazilir.
* Dizinin 5. index numarali elemani '6'. 6<7 oldugu icin Root degerinin soluna dogru yolculuguna baslar. Ardindan 6>5 oldugu icin 5'in sagina yazilir.
* Dizinin 6. index numarali elemani '0'. 0<7 oldugu icin Root degerinin soluna dogru yolculuguna baslar. Ardındn 0<5 ve 0<1 oldugu icin 5'in ve 1'in solundan yolculuguna devam ederek 1'in soluna yazilir.
* Dizinin 7.index numarali elemani '9'. 9>7 oldugu icin Root degerinin sagindan yolculuguna baslar. 9>8 oldugu icin 8'in sagina yazilir.
* Dizinin 8. index numarali elemani '4'. 4<7 oldugu icin Root degerinin solundan yolculuguna baslar. 4<5 oldugu icin 5 degerinin solundan yoluna devam eder. Ardından 4>1 oldugu icin 1'in sagindan yoluna devam ederek 4>3 oldugu icin 3 sayisinin sagina yazilir.
* Dizinin 9. index numarali elemani '2' 2<7 oldugu icin Root degerinin solundan yolculuguna baslar. 2<5 oldugu icin 5 degerinin solundan yoluna devam eder. Ardından 2>1 oldugu icin 1'in sagindan yolun devam ederek 2<3 oldugu icin 3 sayisinin soluna yazilir.                  