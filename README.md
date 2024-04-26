# While-
# O laço While possui uma sintaxe simples: enquanto uma expressão for verdadeira, uma série de instruções será executada de forma repetida. Para imprimirmos na tela os números de 2 a 20, pulando de 2 em 2, poderíamos utilizar o seguinte código:


 <?php

 $i = 2;
 while ($i <= 20) {
	echo $i;
	$i+=2;
	echo "\n";
 }

 /*Sintaxe alternativa*/
 $i = 2;
 while ($i <= 20):
	echo $i;
	$i+=2;
	echo "\n";
 endwhile;
