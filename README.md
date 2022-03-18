#include <stdio.h>
#include <stdlib.h>

void primos()
{
int i, a, b, c;
int primo[a];



        printf("Quantos numeros primos voce deseja:");
        scanf("%i", &a);
            for(b=1;b<a;b++)
            {
                c=0;
                for(i=2;i<=b/2;i++)
                {
                 if(b%i==0)
                 {
                    c=1;
                 }
                }
                if(c==0)
                {
                    printf(" %i ", b);
                }
            }

}
int main()
{
     primos();


    return 0;
}
//sequencia de numeros primos e digite 1 para mostrar a sequencia de numeros primos
