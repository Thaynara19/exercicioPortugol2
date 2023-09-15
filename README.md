programa
{
	inclua biblioteca Util
	
	funcao inicio()
	{
		inteiro numero,inicios,fim,sorteio=1,numeroSorteado,soma=0
		
		escreva("Quantos números você deseja para sorteio : ")
		leia(numero)

		escreva("Começar em qual número ?")
		leia(inicios) 
		
		escreva("Terminar em qual número ?")
		leia(fim)

		escreva("-----------------------------------------\n")
		
		escreva("\tSorteando os ",numero," números\n")

		escreva("-----------------------------------------\n") 
		
		enquanto(sorteio <= numero ){
			
			numeroSorteado = Util.sorteia(inicios,fim)

			escreva(numeroSorteado," - ")

			Util.aguarde(500)
			
			
			soma = soma + numeroSorteado
			
			
			sorteio  = sorteio + 1
			}

			escreva ("\nAcabou >>>>>>>>>>")
			escreva("\nSomando, aguarde . . . . ")
			escreva("\n------------------------------")
		    	escreva("\nA soma do sorteio foi  : ",soma)	
	}
}# exercicioPortugol2
