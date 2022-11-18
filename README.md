# prova2

Algoritmo "Esse algoritimo � uma especie de calculadora"

Var

n1 : vetor [0..1] de real
cont  : inteiro
opcao: inteiro

Inicio

para cont de 0 ate 1 faca

escreval("Digite um n�mero ")
          leia (n1 [cont])

 escreval(" ")

escreval(n1[0], "  " , n1[1])

escreval(" ")

fimpara

enquanto (opcao <> 6) faca

escreval("MENU")

escreval("DIGITE 1 PARA SOMAR ")

escreval("DIGITE 2 PARA SUBTRAIR ")

escreval("DIGITE 3 PARA DIVIDIR ")

escreval("DIGITE 4 PARA MULTIPLICAR")

escreval ("DIGITE 5 PARA POTENCIAL")

escreval("DIGITE 6 PARA SAIR")
         LEIA (opcao)
escreval("")

limpatela

Escolha opcao

caso 1

escreval("O TOTAL �: ", n1[0] + n1[1])

caso 2

escreval("O TOTAL �: ",  n1[0] - n1[1])

caso 3

escreval("O TOTAL �: ", n1[0] / n1[1] )

caso 4

escreval("O TOTAL �: ", n1[0] * n1[1])

caso 5

escreval("O TOTAL �: ", n1[0] ** n1[1])

caso 6

escreval(" ")

outrocaso

escreval("Ops, n�o estava preparado para isso :( ")

fimescolha

escreval(" ")

fimenquanto

se (opcao = 6) entao

escreval("")

escreval("Ate a pr�xima amigo(a)! :)")

fimse

Fimalgoritmo
