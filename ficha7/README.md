# 7º Trabalho de Laboratório - Circuito multiplicador de números inteiros de 8 bits~

A multiplicação de números binários utilizando o algoritmo “Shift-and-add” é executado de forma
semelhante ao da multiplicação “em papel” como se ilustra na figura 1 para números de 4 bits. 

O algoritmo proposto efetua a acumulação (soma) do multiplicando tantas vezes quanto a dimensão do
multiplicador em número de bits. Cada soma do multiplicando é efetuada deslocando-o para a esquerda
depois de multiplicado pelo bit relativo ao produto parcial que é acumulado.

![imagem](/ficha7/f71.PNG)

A implementação do circuito multiplicador faz-se com recurso a dois registos de deslocamento (shift-register) um para o multiplicando e outro para o multiplicador. Será ainda necessário usar um circuito somador acumulador, bem como um circuito de controlo representado por uma máquina de estados.

O objetivo deste trabalho é o de desenvolver um circuito multiplicador de 8 bit usando o simulador Logisim.
