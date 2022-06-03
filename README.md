# Desenho-e-Desenvolvimento-de-Sites
Desenho e Desenvolvimento de Sites
#include <stdio.h>

int main(){
    int idade;
    //Verifica se e maior de idade ou não

    printf ("Digite sua idade:");
    scanf ("%d" , &idade);
    //Estrutura IF

    if ( idade >= 18){
        printf("\nMaior de idade."); //valor se verde
    } else{
        printf("\nMenor de idade.");//valor se falso
    }

    //Verifica se uma pessoa pode votar ou não
    if ( idade < 16 ){
        printf("\nNao pode votar.");

    } else if( idade < 18 ){
        printf("\nVoto opcional.");

    } else if( idade < 70 ){
        printf("\nVoto obrigatorio.");

    } else ( idade >= 70 ){
        printf("\nVoto opcional.");
    }

    //Operador MOD % - retorna o resto de uma divisão
    //Verifica se o numero 10 e divisivel por 2
    // todo numero divisivel por 2 e um numero par
    if ( 10%2 == 0){
        printf("10 eh divisivel por 2.");
    } else{
        printf("\n10 nao eh divisivel por 2");

    }

    return 0;

}
