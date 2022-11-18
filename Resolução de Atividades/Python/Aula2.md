# Repetição:
## Questão 1:
~~~py
for i in range(1000, 2001):
    if i % 11 == 2:
        print(i)

print("\n=================================\n")

contagem = 1000

while contagem <= 2000:
    if contagem % 11 == 2:
        print(contagem)
    contagem += 1
~~~
## Questão 2:
~~~py
acumulo = 0

for i in range(5):
    gasto = float(input(f"Digite o gasto do {i + 1}° cliente: "))
    acumulo += gasto

if acumulo > 54000:
    print(f"Loja A teve um faturamento maior que a loja B com: R${acumulo - 54000} de diferença")
else:
    print(f"Loja A não alcançou o faturamento da loja B ficaram faltando: R${54000 - acumulo}")

print("\n=================================\n")

acumulo = 0
contador = 1

while contador <= 5:
    gasto = float(input(f"Digite o gasto do {contador}° cliente: "))
    acumulo += gasto
    contador += 1
    
if acumulo > 54000:
    print(f"Loja A teve um faturamento maior que a loja B com: R${acumulo - 54000} de diferença")
else:
    print(f"Loja A não alcançou o faturamento da loja B ficaram faltando: R${54000 - acumulo}")
~~~
## Questão 3:
~~~py
contagem = 0

for i in range(10):
    idade = int(input(f"Digite a idade da {i + 1}° pessoa: "))

    if idade >= 18:
        contagem += 1

print(f"O total de pessoas maiores de idade foi/foram: {contagem}") 

print("\n=================================\n")

contagem = 0
rep = 1

while rep <= 10:
    idade = int(input(f"Digite a idade da {rep}° pessoa: "))

    if idade >= 18:
        contagem += 1
    
    rep += 1

print(f"O total de pessoas maiores de idade foi/foram: {contagem}") 
~~~
## Questão 4:
~~~py
num = int(input("Digite o numero final da verificação: "))

for i in range(1, num + 1):
    if i % 2 == 0:
        print(f"{i}")
    else:
        print(i, end="    ")

print("\n=================================\n")


inicio = 1
fim = int(input("Digite o numero final da verificação: "))

while inicio <= fim:
    if inicio % 2 == 0:
        print(f"{inicio}")
    else:
        print(inicio, end="    ")
    
    inicio += 1
~~~
## Questão 5:
~~~py
while True:
    tam = int(input("Digite o tamanho do quadrado entre 1 e 20: "))

    if tam > 1 and tam < 20:
        break

for i in range(0, tam):

    for j in range(0, tam):
        print("*", end=" ")
     
    print()

print("\n=================================\n")


x = 0
y = 0

while x < tam:

    while y < tam:
        print("*", end=" ")
        
        y += 1
    
    print()
    
    y = 0
    x += 1
~~~
## Questão 6:
~~~py
tam = int(input("Digite o tamanho do triangulo: "))

lado = 1

for i in range(tam):
    
    for j in range(lado):
        print("*", end=" ")

    print()
    
    lado += 1

print("===============================")

lado = 1
x = 0
y = 0

while x < tam:

    while y < lado:
        print("*", end=" ")
        y += 1
    
    print()
    
    lado += 1
    y = 0
    x += 1
~~~
## Desafio:
~~~py
num = int(input("Digite o valor da ultima divisão: "))
soma = 0
texto = "1 "

for i in range(1, num + 1):
    soma += 1 / i

    if i != 1:
        texto += f"+ 1/{i} "
    

print(f"Soma = {texto}\n"+
    f"Soma = {soma:.3f}")

print("===============================")

num = int(input("Digite o valor da ultima divisão: "))
soma = 0
texto = "1 "
contagem = 1

while contagem <= num:
    soma += 1 / contagem

    if contagem != 1:
        texto += f"+ 1/{contagem} "
    
    contagem += 1
    

print(f"Soma = {texto}\n"+
    f"Soma = {soma:.3f}")
~~~

https://github.com/GetulioLT/Atividades---l-gica/blob/main/Guias/Python.md
## Menu:
https://github.com/GetulioLT/Atividades---l-gica