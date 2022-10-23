# Entrada e Saída de dados:
## Questão 1:
~~~js
programa
{
	funcao inicio()
	{
		real imc, peso, altura

		escreva("Digite o seu peso: ")
		leia(peso)

		escreva("Digite sua altura: ")
		leia(altura)

		imc = peso / (altura * altura)

		escreva(imc)
	}
}
~~~
## Questão 2:
~~~js
programa
{
	funcao inicio()
	{
		real tc, tf

		escreva("Escreva a temperatura em Fahrenheit: ")
		leia(tf)

		tc = (tf - 32) / 1.8

		escreva(tc)
	}
}
~~~
## Questão 3:
~~~js
programa
{
	funcao inicio()
	{
		real largura, comprimento, area

		escreva("Digite a largura do retangulo: ")
		leia(largura)
		
		escreva("Digite o comprimento do retangulo: ")
		leia(comprimento)

		area = largura * comprimento

		escreva(area)
	}
}
~~~
## Questão 4:
~~~js
programa 
{
	funcao inicio() 
	{
		real v_Brancos, v_Nulos, v_Validos, total
		real p_Nulos, p_Brancos, p_Validos
		
        	escreva("Digite o numero de votos Brancos:\n")
        	leia(v_Brancos)
        
        	escreva("Digite o numero de votos Nulos:\n")
        	leia(v_Nulos)
        
        	escreva("Digite o numero de votos Validos:\n")
        	leia(v_Validos)
        
        	total = v_Brancos + v_Nulos + v_Validos
        
        	p_Nulos = v_Nulos / total * 100
        
        	p_Brancos = v_Brancos / total * 100
        
        	p_Validos = v_Validos / total * 100
        
        	escreva("Percente de Votos Brancos: ", p_Brancos, "\n")
        	escreva("Percente de Votos Nulos: ", p_Nulos, "\n")
        	escreva("Percente de Votos Validos: ", p_Validos, "\n")
	}
}
~~~
## Questão 5:
~~~js
programa 
{
	funcao inicio()
	{
		inteiro a, b, c
		
		a = 10
		b = 20
		
		escreva(a, "\n")
		escreva(b, "\n")
		
		c = a
		a = b
		b = c
		
		escreva(a, "\n")
		escreva(b, "\n")
	}
}
~~~
## Questão 6:
~~~js
programa 
{
	funcao inicio()
	{
		real fab, porDis, porImp, total
		
		escreva("Digite o valor de fabrica do carro: ")
		leia(fab)
		
		porDis = fab * 28 / 100
		porImp = fab * 45 / 100
		
		total = fab + porDis + porImp
		
		escreva("Valor de fabrica: ", fab, "\n")
		escreva("Valor de Distribuidor: ", porDis, "\n")
		escreva("Valor de Impostos: ", porImp, "\n")
		escreva("Valor total do carro: ", total)
	}
}
~~~
# Condicionais:
## Questão 1:
~~~js
programa 
{
	funcao inicio()
	{
		inteiro num
		
		escreva("Digite um numero qualquer inteiro: ")
		leia(num)
		
		se(num > 0)
		{
		    escreva("Esse numero é positivo e ")
		    se(num % 2 == 0)
		    {
		        escreva("par")
		    }
		    senao
		    {
		        escreva("impar")
		    }
		}
		senao
		{
		    escreva("Esse numero é negativo")
		}
	}
}
~~~
## Questão 2:
~~~js
programa 
{
	funcao inicio()
	{
		real temp
		logico cancela
		
		escreva("Digite a temperatura da pessoa: ")
		leia(temp)
		
		se(temp <= 37)
		{
		    cancela = verdadeiro
		}
		senao
		{
		    cancela = falso
		}
		
		escreva(cancela)
	}
}
~~~
## Questão 3:
~~~js
programa 
{
	funcao inicio()
	{
		real indice
		
		escreva("Digite o valor do indice de poluição: ")
		leia(indice)
		
		se(indice >= 0.05 e indice < 0.25)
		{
		    escreva("Aceitavél")
		}
		senao se(indice <= 0.3)
		{
		    escreva("1° grupo, atividades suspensas")
		}
		senao se(indice <= 0.04)
		{
		    escreva("1° e 2° grupo, atividades suspensas")
		}
		senao se(indice <= 0.05)
		{
		    escreva("Todos os grupo, atividades suspensas")
		}
	}
}
~~~