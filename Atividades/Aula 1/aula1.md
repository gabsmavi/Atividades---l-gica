# Atividades aula 1:

## Entrada e saida de dados:
#
<h3>
1°: Crie um algoritmo para calcular o IMC do usuário.
IMC = peso / altura²

<h3>
2°: Transformar uma temperatura de Fahrenheit para Celsius.
<h3>
TC = (TF - 32) / 1,8
<h3>
TC: Temperatura em Celsius.
<h3> 
TF: Temperatura em Fahrenheit.

<h3>
3°: Escreva um algoritmo para ler as dimensões de um retângulo (largura e comprimento), calcular e escrever a área do retângulo.
<h3>
retangulo = largura * comprimento

<h3>
4°: Escreva um algoritmo para ler o número total de eleitores de um município, o número de votos brancos, nulos e válidos. Calcular e escrever o percentual que cada um representa em relação ao total de eleitores.
<h3>
Dica: O total de eleitores será a soma de todos os votos

<h3>
5°: Escreva um algoritmo que armazene o valor 10 em uma variável A e o valor 20 em uma variável B. A seguir (utilizando apenas atribuições entre variáveis) troque os seus conteúdos fazendo com que o valor que está em A passe para B e vice-versa. Ao final, escrever os valores que ficaram armazenados nas variáveis.

<h3>
6°: O custo de um carro novo ao consumidor é a soma do custo de fábrica com a porcentagem do distribuidor e dos impostos (aplicados ao custo de fábrica). Supondo que o percentual do distribuidor seja de 28% e os impostos de 45%, escreva um algoritmo para ler o custo de fábrica de um carro, calcular e mostrar o custo final ao consumidor. 

#
## Condicionais:
#

</h3>
1°: Solicite um número ao usuário e mostre se o número é positivo ou negativo. Se o numero for positivo mostre se ele é impar ou par.

</h3>
2°: A cancela de um estabelecimento, em momento de pandemia, funciona dependendo da temperatura aferida e registrada pelo recepcionista do local. É preciso criar um algoritmo para liberar ou não a cancela dependendo da temperatura corporal. Com um medidor o recepcionista irá aferir e registrar no sistema e o algoritmo deverá liberar caso a temperatura seja <= 37 e não liberar caso a temperatura seja maior que 37º.
A cancela só recebe True ou False (True para liberar e False para bloquear)

</h3>
3°: Leia um numero real. Se o numero for positivo imprima a raiz quadrada. Do contrario,  imprima o numero ao quadrado. 

</h3>
4°: A Secretaria de Meio Ambiente que controla o índice de poluição mantém 3 grupos de indústrias que são altamente poluentes do meio ambiente. O índice de poluição aceitável varia de 0,05 até 0,25. Se o índice sobe para 0,3 as indústrias do 1º grupo são intimadas a suspenderem suas atividades, se o índice crescer para 0,4 as indústrias do 1º e 2º grupo são intimadas a suspenderem suas atividades, se o índice atingir 0,5 todos os grupos devem ser notificados a paralisarem suas atividades. Faça um algoritmo que leia o
índice de poluição medido e emita a notificação adequada aos diferentes grupos de empresas.

</h3>
5°:Ler o nome de 2 times e o número de gols marcados na partida (para cada time).
E no final escrever o nome do vencedor. Caso não haja vencedor deverá ser impressa a palavra EMPATE.

</h3>
6°: Desenvolva um algoritmo que solicite o preço de três produtos e informe qual produto deve ser comprado, sabendo que a decisão é sempre pelo mais barato.

</h3>
7°: Uma empresa quer verificar se um empregado está qualificado para a aposentadoria ou não. Para isso tem que se ter um dos seguintes requisitos:


1) Ter no mínimo 65 anos de idade. 
2) Ter trabalhado no mínimo 30 anos. 
3) Ter no mínimo 60 anos e ter trabalhado no mínimo 25 anos. 

</h3>
Faça um algoritmo que leia: o número do empregado (código), o ano de seu nascimento e o ano de seu ingresso na empresa.
 O programa deverá escrever a idade e o tempo de trabalho do empregado e a mensagem 'Requerer aposentadoria' ou 'Não requerer'.
Use: DateTime.Now.Year, para pegar o valor do ano atual.