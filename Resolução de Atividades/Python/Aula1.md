# Condicionais:
## Questão 1:
~~~py
num1 = float(input("Digite o primeiro numero: "))
num2 = float(input("Digite o segundo numero: "))

if num1 > num2:
    print(f"O numero {num1} é maior que o numero {num2}")
else:
    print(f"O numero {num2} é maior que o numero {num1}")


print("=================================")

num3 = float(input("Digite o primeiro numero: "))
num4 = float(input("Digite o segundo numero: "))

print(f"O numero {num3} é maior que o numero {num4}" if num3 > num4 
else f"O numero {num4} é maior que o numero {num3}")
~~~
## Questão 2:
~~~py
num = float(input("Digite o primeiro numero: "))

if num > 0:
    print(f"O numero {num} é positivo")
else:
    print(f"O numero {num} é negativo")

print("=================================")

num2 = float(input("Digite o primeiro numero: "))

print(f"O numero {num2} é positivo" if num2 > 0
else f"O numero {num2} é negativo")
~~~
## Questão 3:
~~~py
letra = input("Digite F para feminino e M para masculino: ")

if letra.upper() == "F":# .upper deixar toda a string com letras maisculas idependentemente do texto
    print("Feminino")
else:
    if letra.lower() == "M":# .lower deixar toda a string com letras minuscula idependentemente do texto
        print("Masculino")
    else:
        print("Indefinido")
~~~
## Questão 4:
~~~py
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))

media = (nota1 + nota2) / 2

if media == 10:
    print("Aprovado com Distinção")
elif media >= 7:
    print("Aprovado")
else:
    print("Reprovado")


print("============================")

print("Aprovado com Distinção" if media == 10
else "Aprovado" if media >= 7
else "Reprovado")
~~~
## Questão 5:
~~~py
num1 = float(input("Digite o primeiro numero: "))
num2 = float(input("Digite o segundo numero: "))
num3 = float(input("Digite o terceiro numero: "))


if num1 > num2 and num1 > num3:
    print(f"O numero {num1} é o maior")
elif num2 > num1 and num2 > num3:
    print(f"O numero {num2} é o maior")
else:
    print(f"O numero {num3} é o maior")


print("\n===========================================\n")

print(f"O numero {num1} é o maior" if num1 > num2 and num1 > num3 else
f"O numero {num2} é o maior" if num2 > num1 and num2 > num3 else
f"O numero {num3} é o maior")
~~~
## Questão 6:
~~~py
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))

media = (nota1 + nota2) / 2

if media >= 9 and media <= 10:
    print("Nota Conceito A")
elif media >= 7.5: # Não é preciso colocar media < 9, pois pela primeira estrutura já se sabe que será menor que 9
    print("Nota Conceito B")
elif media >= 6:
    print("Nota Conceito C")
elif media >= 4:
    print("Nota Conceito D")
else:
    print("Nota Conceito E")


print("\n===========================================\n")

print("Nota Conceito A" if media >= 9 and media <= 10 else
"Nota Conceito B" if media >= 7.5 else
"Nota Conceito C" if media >= 6 else
"Nota Conceito D" if media >= 4 else
"Nota Conceito E")
~~~
## Desafio:
~~~py
combustivel = input("Digite A para alcool e G para gasolina: ")
litros = float(input("Digte a quantidade de combustivel: "))

if combustivel.lower() == "a":
    valor = litros * 5.40

    if litros <= 20:
        desconto = valor * 3 / 100
    else:
        desconto = valor * 4 / 100

    valor_final = valor - desconto
    print(f"O valor a pagar será: R${valor_final:.2f}")
else:
    valor = litros * 4.70

    if litros <= 20:
        desconto = valor * 4 / 100
    else:
        desconto = valor * 6 / 100

    valor_final = valor - desconto
    print(f"O valor a pagar será: R${valor_final:.2f}")
~~~

## Atividades: <br>
https://github.com/GetulioLT/Atividades---l-gica/blob/main/Guias/Python.md
## Menu:
https://github.com/GetulioLT/Atividades---l-gica