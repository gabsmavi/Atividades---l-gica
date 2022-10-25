# Entrada e Saída de dados:
## Questão 1:
~~~python
peso = float(input('Digite seu peso: '))
altura = float(input('Digite seu altura: '))

imc = peso / altura ** 2

print(f'seu imc é igual : {imc}')
~~~
## Questão 2:
~~~python
tf = float(input('Digite a temperatura em fahrenheit: '))

tc = (tf - 32) / 1.8

print(f'A temperatura em celcis é igual a: {tc}')
~~~
## Questão 3:
~~~python
largura = float(input('Digite a largura do retangulo: '))
comprimento = float(input('Digite a comprimento do retangulo: '))

retangulo = largura * comprimento

print(f'A area do Retângulo é igua a: {retangulo}')
~~~
## Questão 4:
~~~python
vBrancos = int(input('Digite a quantidade de votos Brancos: '))
vNulos = int(input('Digite a quantidade de votos Nulos: '))
vValidos = int(input('Digite a quantidade de votos Validos: '))

total = vValidos + vNulos + vBrancos

pValidos = vValidos / total * 100
pBrancos = vBrancos / total * 100
pNulos = vNulos / total * 100

print(f'O percente de votos:\n' +
f'Votos Validos: {pValidos}\n' +
f'Votos Brancos: {pBrancos}\n' +
f'Votos Nulos: {pNulos}')
~~~
## Questão 5:
~~~python
a, b = 10, 20

print(a, b)

a, b = b, a

print(a, b)
~~~
## Questão 6:
~~~python
valorFabrica = float(input('Digite o valor de Fabrica do carro: '))

total = valorFabrica + (valorFabrica * 28 / 100) + (valorFabrica * 45 / 100)

print(f'O valor do carro no final ficou num total de: R${total}')
~~~

# Condicionais:
## Questão 1:
~~~py
num = float(input('Digite um numero qualquer Real: ')

if num > 0:
    if num % 2 == 0:
        print(f'O numero {num} é par')
    else:
        print(f'O numero {num} é impar')
elif num < 0:
    print(num ** 2)
else:
    print('Numero igual a zero')
~~~
## Questão 2:
~~~py
temp = float(input('Digite o valor da tempera da pessoa: '))

if temp <= 37:
    passagem = True
else:
    passagem = False

print(f'Após a verificação de acordo com o resultado sendo ele True para passagem liberada e False para barrrado: {passagem}')
~~~
## Questão 3:
~~~py
indice = float(input('Digite o valor do indice de poluição: '))
if indice >= 0.05 e indice < 0.25:
    print('Aceitavél')
elif indice <= 0.04:
	print('1° grupo, atividades suspensas')
elif indice <= 0.05:
    print('1° e 2° grupo, atividades suspensas')
elif indice > 0.05:
    print('Todos os grupo, atividades suspensas')
~~~
## Questão 4:
~~~py
timeA = input('Digite o nome do primeiro time: ')
timeB = input('Digite o nome do segundo time: ')

golsA = int(input(f'Digite os gols do time {timeA}: '))
golsB = int(input(f'Digite os gols do time {timeB}: '))

if golsA > golsB:
    print(f'O time {timaA} venceu o time {timeB}')
elif golsA < golsB:
    print(f'O time {timaB} venceu o time {timeA}')
else:
    print('Os times empataram')
~~~
## Questão 5:
~~~py
precoA = float(input('Digite o valor 1: '))
precoB = float(input('Digite o valor 2: '))
precoC = float(input('Digite o valor 3: '))

if precoA > precoB and precoA > precoC:
    print(f'O valor de {precoA}R$ deve ser comprado')
elif precoB > precoC and precoB > precoA:
    print(f'O valor de {precoB}R$ deve ser comprado')
else:
    print(f'O valor de {precoC}R$ deve ser comprado')
~~~
## Questão 6:
~~~py
num_empre = int(input("Digite o codigo do empregado: "))
ano_nasci = int(input("Digite o ano de nascimento do empregado: "))
ano_ingre = int(input("Digite o ano de ingresso do empregado: "))

idade = 2022 - ano_nasci
tp_tra = 2022 - ano_ingre
		
if idade >= 65 ou tp_tra >= 30 ou (idade >= 60 e tp_tra >= 25):
    print(f"O empregado de codigo: {num_empre} com {idade} anos e {tp_tra} de empresa pode requerer aposentadoria")
else:
    print("Não pode requerer a aposentadoria")

~~~