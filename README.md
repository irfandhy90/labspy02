# labspy02

## Soal 

![img](gambar/ss1.png)

## Jawab

untuk menjawab soal tersebut saya membuat inputan data nilai sebagai berikut : 

    a = int(input("Masukkan bilangan 1: "))
    b = int(input("Masukkan bilangan 2: "))
    c = int(input("Masukkan bilangan 3: "))

kemudian masukan angka yang di inginkan 

saya masukan bilangan 1 = 4 bilangan 2 = 6 bilangan 3 = 8 

lalu masukan flowchart seperti di bawah ini : 

![img](gambar/ss2.png)

setelah itu saya menggunakan syntax di bawah ini : 

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

## output 

Dari syntax di atas menggunakan output berikut : 

![img](gambar/gambar1.png)

Terima kasih 





