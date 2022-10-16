# Veri Yapları ve Algoritmalar Proje-1-2-3
Bu repo [Patika.dev](https://www.patika.dev/tr) GIT konusu altında oluşturduğumuz ilk repo. İçerisinde bir adet README dosyası, bir adet de index.hmtl barındırıyor.

<p align="center" width="100%">
    <img width="25%" src="https://global-uploads.webflow.com/6097e0eca1e87557da031fef/609859a191abe5d64b17fed3_Patika%20logo-p-500.png"> 
</p>

# Content

Proje 1

    [22,27,16,2,18,6] -> Insertion Sort

    a-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    b-Big-O gösterimini yazınız.
    c-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    d-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    a
    0=[22,27,16,2,18,6]
    1=[2,27,16,22,18,6]
    2=[2,6,16,22,18,27]
    3=[2,6,16,18,22,27]

    b
    n+(n-1)+(n-2)+....1
    (n.(n+1)).1/2
    O(n2)

    c
    avarage case

    d
    0=[7,3,5,8,2,9,4,15,6]
    1=[2,3,5,8,7,9,4,15,6]
    2=[2,3,4,8,7,9,5,15,6]
    3=[2,3,4,5,7,9,8,15,6]
    4=[2,3,4,5,6,9,8,15,7]
    5=[2,3,4,5,6,7,8,15,9]
    6=[2,3,4,5,6,7,8,9,15]


Proje 2

    [16,21,11,8,12,22] -> Merge Sort

    a-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    b-Big-O gösterimini yazınız.

    a
    0=		       [16,21,11,8,12,22]
    1=	     [16,21,11]	      [8,12,22]
    2=	[16,21] [11]             [8,12] [22]
    3=   [16] [21] [11]               [8] [12] [22]
    4=	[16,21] [11]             [8,12] [22]
    5=	     [11,16,21]	       [8,12,22]
    6=		      [8,11,12,16,21,22]

    b
    O(nlogn)	


    Proje 3

    [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    root=7 

			7
		      5   8
		    1       9
		  0   3
			6 
		      4
		    2 
            
# Installation
Öncelikle projeyi klonlayın.(Buraya sizin reponuzdan aldığınız link gelecek)
```
git clone https://github.com/ilkaysefer/Veri-Yap-lar-ve-Algoritmalar-Proje-1-2-3.git
```

# Usage

Projeyi klonladıktan sonra Visual Studio Code programında açınız.

Linux için:
```
cd Veri Yapları ve Algoritmalar Proje-1-2-3
code .
```

# Contributing

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License
[MIT](https://choosealicense.com/licenses/mit/)
