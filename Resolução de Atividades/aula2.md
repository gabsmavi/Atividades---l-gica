# Entrada e Saída de dados:
## Questão 1:
~~~js
programa 
{
  funcao inicio() 
  {
    real num, mul, div

    escreva("Digite um numero qualquer real: ")
    leia(num)

    escreva("Multiplicação: \n")
    para(inteiro i = 1; i <= 10; i++)
    {
      mul = num * i

      escreva(num, " x ", i, " = ", mul, "\n")
    }

    real contador = 1

    escreva("Divisão: \n")

    enquanto(contador <= 10)
    {
      div = num / contador

      escreva(num, " / ", contador, " = ", div, "\n")
      
      contador++
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
    para(inteiro i = 1000; i <= 2000; i++)
    {

      se(i % 11 == 2)
      {
        escreva(i, "\n")
      }

    }

    escreva("=============================\n")

    inteiro contador = 1000

    enquanto(contador <= 2000)
    {
      se(contador % 11 == 2)
      {
        escreva(contador, "\n")
      }

      contador++
    } 
  }
}
~~~
## Questão 3:
~~~js
programa 
{
  funcao inicio() 
  {
    
    inteiro tam

    escreva("Digite o tamanho do quadrado: ")
    leia(tam)

    para(inteiro i = 0; i < tam; i++)
    {
      para(inteiro j = 0; j < tam; j++)
      {
        escreva("* ")
      }
      escreva("\n")
    }

    escreva("\n==========================================\n\n")

    inteiro x = 0, y = 0

    enquanto(x < tam)
    {
      enquanto(y < tam)
      {
        escreva("* ")
        y++
      }
      escreva("\n")
      y = 0
      x++
    }

  }
}
~~~
## Questão 4:
~~~js
programa 
{
  funcao inicio() 
  {
    
    real idade = 1, contagem = 0, acumulador = 0, media

    enquanto(idade != 0)
    {
      escreva("Digite a idade: ")
      leia(idade)

      se(idade != 0)
      {
        contagem++
        acumulador = acumulador + idade
      }
    }

    media = acumulador / contagem

    escreva("A media das idade é igual a: ", media)
  }
}
~~~