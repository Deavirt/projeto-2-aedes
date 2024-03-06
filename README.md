#include <stdio.h>
#include <stdlib.h>

int main(void) {
	int x, y, result, cont;
	cont = 1;

	while (cont <=3 ) {
		printf("Entre com dois números para serem somados: ");
		fflush(stdout);
		scanf("%d %d" , &y, &x);

		result= x + y;

		printf("O resultado da soma é %d\n", result);

		cont = cont + 1;

	for (cont = 1; cont <=3; cont++) {
		printf("Entre com dois números para serem somados: ");
		fflush(stdout);
		scanf("%d %d" , &x ,&y);

		result = x + y;

		printf("O resultado da soma é:%d\n", result);
		}
	}

		return 0;

	}
