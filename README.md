# Eric7
💻 Primeiros passos com a linguagem C

Segue abaixo alguns codigos que ja produzi pela faculdade

1 - Calculando as notas da prova 1 e 2 e calculando a media para ser aprovado no semestre

#include<stdio.h>
#include<string.h>

int main (){

 float np1, np2, media;
 
 printf("Digite a nota 1: ");
 scanf("%f", &np1);
 
 printf("Digite a nota 2: ");
 scanf("%f", &np2);
 
 media = (np1 + np2)/2;
 
 if (media >= 5){
 printf ("Aprovado \n");
 
 }else{
 printf ("Reprovado \n");
 }
 printf("A sua nota foi %.2f ", media);
 return 0;
} 

2 - Calculando a área de um cilindro 

#include <stdio.h>
#include <stdlib.h>

#define pi=3.14

int main(){

   int raio;
   int volume;
   int altura;

   printf("Digite o valor do cilindro");
   scanf("%d",&valor);

   printf("Digite o volume do cilindro");
   scanf("%d",volume);

   printf("Digite a altura do cilindro");
   scanf("%d",&altura);

   valor=3.14*raio*5
}
