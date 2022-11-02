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
## Questão 5:
~~~js
programa 
{
  funcao inicio() 
  {
    real valor_compra = 500.0
    real valor_final, desconto

    para(inteiro i = 1; i <= 25; i++)
    {
      desconto = valor_compra * i / 100

      valor_final = valor_compra - desconto

      escreva(valor_compra, "R$ - ", i, "% - ", valor_final, "R$\n")

      valor_compra += 100
    }

    escreva("\n============================================\n\n")

    inteiro contador = 1

    valor_compra = 500.0

    enquanto(contador <= 25)
    {
      desconto = valor_compra * contador / 100

      valor_final = valor_compra - desconto
      
      escreva(valor_compra, "R$ - ", contador, "% - ", valor_final, "R$\n")

      valor_compra += 100
      contador++
    }
  }
}
~~~
## Questão 6:
~~~js
programa 
{
  funcao inicio() 
  {
    
    real cad1 = 0, cad2 = 0, cad3 = 0, cad4 = 0, nulo = 0, branco = 0, total
    inteiro voto = 1

    enquanto(voto != 0)
    {

      escreva("Eleições 2022:\nDigite os seguintes numeros para cada operações:\n")
      escreva("1 - eleitor 1\n2 - eleitor 2\n3 - eleitor 3\n4 - eleitor 4\n")
      escreva("5 - Nulo\n6 - Branco\n0 - Finalizar\n")
      leia(voto)

      se(voto != 0)
      {
        
        se(voto == 1)
        {
          cad1++
        }
        senao se(voto == 2)
        {
          cad2++
        }
        senao se(voto == 3)
        {
          cad3++
        }
        senao se(voto == 4)
        {
          cad4++
        }
        senao se(voto == 5)
        {
          nulo++
        }
        senao
        {
          branco++
        }

      }
    }

    total = cad1 + cad2 + cad3 + cad4 + nulo + branco

    escreva("Final da Eleioção. Apurado de Votos:\n")
    escreva("cadidato 1: ", cad1, "\n")
    escreva("cadidato 2: ", cad2, "\n")
    escreva("cadidato 3: ", cad3, "\n")
    escreva("cadidato 4: ", cad4, "\n")
    escreva("nulo: ", nulo, "\n")
    escreva("branco: ", branco, "\n")
    escreva("percentagem nulo: ", (nulo / total) * 100, "%\n")
    escreva("percentagem branco: ", (branco / total) * 100, "%\n")

  }
}
~~~