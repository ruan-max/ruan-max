#include<stdio.h>

/*

int main()
{

    int inteira=10;
    char caractere= 'A';
    float decimal= 12.455;
  
   printf("%i\n", inteira);
   
   printf("%f\n", decimal);
 
   printf("%c\n", caractere);
 
   return 0;

}
*/


int main()

{

    float num1, num2, div, mult, soma, sub;

 
  div= num1/num2;
 
  mult= num1*num2;
 
  soma= num1+num2;
  
  sub= num1 - num2;
    
    printf(" digite o primeiro número\n");
    scanf("%f", &num1);

    printf("digite o segundo número\n");
    scanf("%f", &num2);
    
    div= num1/num2;
    printf("\n A divisão é: %f\n", div);
   
     mult= num1*num2;
    printf(" A multiplicação é :%f\n", mult);
  
      soma= num1+num2;
    printf(" A soma é: %f\n", soma);
  
      sub= num1 - num2;
    printf(" A subtração é: %f\n", sub);

    printf(" esses são os valores com casas decimais");

return 0;
}
