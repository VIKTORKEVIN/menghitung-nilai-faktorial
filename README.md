# menghitung-nilai-faktorial

    #include<iostream>
    #include<conio.h>

    using namespace std;
    int main()
    {
    int bil, n;
    long int hasil;

    cout<<"==Mencari nilai faktorial==";
    cout<<"\n==dari bilangan desimal==";
    cout<<"\n============================";
    cout<<"\n\n Masukkan angka= ";
    cin>>n;

    hasil=1;
    for(bil=n; bil>=1; bil--)
    {
        hasil=hasil*bil;
    }
    cout<<"Hasil Faktorial= "<<hasil<<"\n";
    getch ();
    }
    
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/menghitung-nilai-faktorial/master/menghitung%20nilai%20faktorial.png)
