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