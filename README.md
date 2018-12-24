# Contoh-By-Value

codingan program lengkap

    #include<stdio.h>
    void secara_nilai(float a,float b,char c)
    {
     float *Alamat_A;
     a = 7;
     printf("lokal A = %f, alamat A = %p\n",a,Alamat_A);
     printf("lokal B = %f\n",b);
     printf("lokal C = %c\n",c);
    }
    int main()
    {
    float a=25,*Alamat_A;
    char c = 'a';
    Alamat_A = &a;
    secara_nilai(a,a/3,c);
    printf("main A = %f, alamat A = %p\n",a,Alamat_A);
    printf("main A/3 = %f\n",(a/3));
    printf("main c = %c\n",c);
    return 0;
    }
    
hasil program 

![img](https://github.com/AbdulahHanafi/Contoh-By-Value/blob/master/Contoh%20By%20Value%20algo8.png?raw=true)
