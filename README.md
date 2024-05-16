# att10.10

#include  <stdio.h>
#include  <stdlib.h>

int  principal (){

	int  valorUm ;
	int  valorDois ;
	int  valorNovo ;

	printf ( "Escreva o valor 1:" );
	scanf ( "%i" , & valorUm );
	printf ( "Escreva o valor 2:" );
	scanf ( "%i" , & valorDois );

	printf ( "\nValor da primeira variável: %i" , valorUm );
	printf ( "\nValor da segunda variável: %i" , valorDois );

	valorNovo  =  valorUm ;
	valorUm  =  valorDois ;
	valorDois  =  valorNovo ;

	printf ( "\nNovo valor da primeira variável: %i" , valorUm );
	printf ( "\nNovo valor da segunda variável: %i" , valorDois );


	retornar  0 ;
}
