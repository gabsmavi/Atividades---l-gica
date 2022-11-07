# Entrada e Saída de dados:
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

if letra.upper() == "F":# .upper deixar toda a string com letras maisculas idependente do texto
    print("Feminino")
else:
    if letra.upper() == "M":
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