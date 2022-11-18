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

https://github.com/GetulioLT/Atividades---l-gica/blob/main/Guias/Python.md
## Menu:
https://github.com/GetulioLT/Atividades---l-gica