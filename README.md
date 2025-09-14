#include <stdio.h>

		//movimentação do bispo

void moverbispo(int casas) {
    if (casas > 0) {
        printf("Movendo o bispo 1 casa para a diagonal direita para cima\n");
        moverbispo(casas - 1);
        printf("\n");
    }
}
	
			// movimento da torre
void movertorre(int casas){
	if(casas > 0){
		printf("Movendo a torre 1 casa para a direita\n");
		movertorre(casas - 1);
		printf("\n");
	}
}
		//movimento da rainha
void moverrainha(int casas){
	if(casas > 0){
		printf("Mover rainha 1 casa pra esquerda\n");
		moverrainha(casas - 1);
		printf("\n");
	}
}
		//movimento do cavalo
void movercavalo(int movimentos){
	if(movimentos > 0){
		printf("Movendo o cavalo duas casas para cima e uma para direita\n");
		movercavalo(movimentos - 1);
	}
}



int main() {
    moverbispo(5);
    movertorre(5);
    moverrainha(8);
    movercavalo(3);
    
    
    
    
	return 0;
	
	
	
}

