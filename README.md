# sayi-yuvarlama-algoritmasi
```C
#include <stdio.h>
#include <stdlib.h>

int main()
{
    float x,a,y,z,t,k,b,c;
    b=0.0;
    printf("bir sayı giriniz\n");
    scanf("%f", &x);
    k=x;
    if(x>1){
    while(x>1){
        x=x-1;
    }
    if(x>=0.5){
    a=1-x;
    y=a+k;
    printf("%f",y);
    }
    else{
        c=k-x;
        printf("%f",c);
    }
    }
    else{
        if(x>=0.5){
        z=1-x;
        t=x+z;
        printf("%f",t);
        }
        else{
            printf("%f",b);
        }
    }
    
    return 0;
}
```
