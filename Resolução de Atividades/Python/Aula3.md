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

https://github.com/GetulioLT/Atividades---l-gica/blob/main/Guias/Python.md
## Menu:
https://github.com/GetulioLT/Atividades---l-gica