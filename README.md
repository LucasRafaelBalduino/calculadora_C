# calculadora_C
// calculadora_simples.cpp : Define o ponto de entrada para a aplicação de console.
//

#include "stdafx.h"
#include <iostream>
#include <stdlib.h>



	
int LerNumeroInteiro() {
	printf_s("Calculadora Top:\n");
	int numero;
	scanf("%i", &numero);
	//int sub, mais, div, mult;
	//scanf("%i", &calc);
	return numero;
}

char Operador() {
	printf("Qual é a operacao?");
		char oper;
		scanf("%i", &oper);
		return oper;
}


float Calculadora_Soma(int a, int b){
	return (a + b);
}

float Calculadora_Subtracao(int a, int b) {
	return (a - b);
}

float Calculadora_Divicao(int a, int b) {
	return (a * b);
}

float Calculadora_Multiplicacao(int a, int b) {
	return (a / b);
}

char Resultado_Calculadora() {

}

int main()
{


	int primeiroNumero = LerNumeroInteiro();
	int segundoNumero = LerNumeroInteiro();
	int s = Calculadora_Soma(primeiroNumero, segundoNumero);
	printf_s("O resultado: %i \n", s);
	system("pause");

}
