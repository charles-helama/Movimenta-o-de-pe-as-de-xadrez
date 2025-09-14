# Movimenta-o-de-pe-as-de-xadrez
Criando um código seguindo as especificações dadas pelo professor.
#include <stdio.h>

int main(){
	
	int i=0;
	int movimentocompleto = 1; //para contolrar movimento em L
	
	while(i < 4){
		printf("Torre pra cima %d\n", i); // movimento da torre
		i++;
		printf("\n");
	}
	
	
	do {
		printf("Rainha para lado direito %d\n",i); //movimento da rainha
		i++;
		
	} while(i <=7 );
	
	printf("\n");
	
	
	for (i=0;i<5; i++){
		printf("Bispo pra cima lado esquerdo %d\n", i);//movimento do bispo
	}
	rintf("\n); //logo abaixo movimento do cavalo.
	while(movimentocompleto--);{
		
	for(i=0; i<2; i++){
		
		printf("cima\n"); //movimenta duas vezes(duas casas)
	}	
		printf("Direita\n");//movimento para a direita
	}
	
		
		
		
	
	
	
}