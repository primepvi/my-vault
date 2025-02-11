Um array é uma DSA (data-structure) que nos permite armazenar uma quantidade fixa elementos de mesmo tipo (tamanho em bits) de forma sequencial na memória (um elemento após  o outro), ou seja, é inflexível (não redimensionável). Em caso de necessidade de adicionar mais elementos do que a capacidade inicial do array permite, temos que realocar todos os elementos para um novo bloco de memória que satisfaça nossa necessidade de aumento de capacidade.

![[Pasted image 20241015212342.png]]

##### Por que é necessário realocação para aumento de capacidade?
Considerando que, quando declaramos um array com sua capacidade inicial é requisitado ao sistema operacional que encontre um local na memória que satisfaça nossas necessidades, que no caso são:
-  bloco de memória de x bits, sendo x igual a capacidade inicial do array multiplicado pelo tamanho em bits do tipo do array (ex: int de 16 bits).
-  esse bloco de memória deve ser sequencial (o famoso linguição de bits).

Portanto, através dessas necessidades percebe-se que dificilmente os endereços adjacentes ao nosso bloco de memória estarão disponíveis, de tal forma que a melhor opção é realocar um novo bloco de memória com o dobro de capacidade.