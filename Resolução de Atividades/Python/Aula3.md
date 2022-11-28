# Listas:
## Questão 1:
~~~py
lista_numerica = list()

for i in range(12):
    numero = int(input("Digite um numero qualquer: "))
    lista_numerica.append(numero)

print(lista_numerica)

x = int(input("Digite uma posição de 0 a 11: "))
y = int(input("Digite outro posição de 0 11: "))

soma = lista_numerica[x] + lista_numerica[y]

print(f"A soma das duas posições é: {soma}")
~~~
## Questão 2:
~~~py
lista_impares = list()

while True:
    num = int(input("Digite um numero qualquer: "))

    if num % 2 != 0:
        lista_impares.append(num)

        if len(lista_impares) == 10:
            print(lista_impares)
            break
~~~
## Questão 3:
~~~py
lista_numerica = list()

contador = 0

for i in range(10):
    numero = int(input("Digite um numero qualquer: "))

    lista_numerica.append(numero)

x = int(input("Digite um numero para verificar se exixte na lista: "))

for j in lista_numerica:
    if j == x:
        print(f"O numero: {x}, está na posição: {contador}")
        break
    contador += 1
else:
    if x not in lista_numerica:
        print("Numero não encontrado")
~~~
## Questão 4:
~~~py
lista_numerica = list()

contador = 0

for i in range(10):
    numero = int(input("Digite um numero qualquer: "))

    lista_numerica.append(numero)

x = int(input("Digite um numero para verificar se exixte na lista: "))

for j in lista_numerica:
    if j == x:
        print(f"O numero: {x}, está na posição: {contador}")
        break
    contador += 1
else:
    if x not in lista_numerica:
        print("Numero não encontrado")
~~~

https://github.com/GetulioLT/Atividades---l-gica/blob/main/Guias/Python.md
## Menu:
https://github.com/GetulioLT/Atividades---l-gica