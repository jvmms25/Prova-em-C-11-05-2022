# Prova-em-C-11-05-2022
Aqui está todas as atividades da prova, da 1 até a 7;

#include <stdio.h>
#include <locale.h>


int main(){
	setlocale(LC_ALL,"Portuguese");

		
		char categoria;
		float quantidade, soma, total, media;
		
		do
		{
			printf("Informe a categoria\n");
			scanf(" %c", &categoria);
			
			printf("Informe a quantidade\n");
			scanf(" %f", &quantidade);
			
			soma = soma + quantidade;
			total++;
			media = soma / total;
			
		}while(categoria == 'A' || categoria == 'B');
		
		printf("A media dos produtos é %.2f", media);
		
		
		
		return 0;

}

