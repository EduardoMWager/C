#include <iostream>
#include <stdlib.h>
#include <stdio.h>
#include <locale.h>
#include <conio.h>
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
char op=0;
    setlocale(LC_ALL,"portuguese");//permite usar ~ e ç
            while(op!= '0')
            {
                printf("\nDigite uma das opções abaixo:");
                printf("\n0 para sair.");
                printf("\n1 para números primos.");
                printf("\n2 para sequência de fibonacci.\n");
                op = getch();
                    if(op=='1')
                    {
                        primos();
                    }

                   // else if(op=='2')
                       // fibonacci
                      // printf("n fiz ainda sorry");
                    else if(op=='0')
                        printf("\n VC QUE QUIS SAIR KRL N CHORA AGR");
                    else
                        printf("\n DIGITA UM BGL CERTO DESGRAÇA É UM OU DOIS DESGRAÇA.");
            }


    return 0;
}
