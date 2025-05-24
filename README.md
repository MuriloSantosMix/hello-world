# hello-world
primeiro repositório de programador
// Aprendendo a quebrar linhas na programação
    escreva ("Curso:\nLógica de Programação\n")
    ("_______________________________________________________________________________")
    
    // Aprendizado de como colocar informações para usuários
    cadeia nome
    inteiro idade 

    escreva("Digite seu nome: ")
    leia(nome)
    escreva("Digite sua idade: ")
    leia(idade)

    escreva(nome, " possui a idade de ", idade, " anos\n ")


    
    // Aprendendo a forma de imprimir as informações para usuários
    escreva(" Forma para aparecer informações para o usuário\n")
    cadeia nome
    inteiro idade 

    escreva("Digite seu nome: ")
    leia(nome)
    escreva("Digite sua idade: ")
    leia(idade)

    escreva(nome, " possui a idade de ", idade, " anos\n ")

    
    // Aprendizado de como realizar o cálculo de média 
    escreva(" Cálculo de média\n")
    cadeia nome
    inteiro nota_1
    inteiro nota_2
    inteiro nota_3
    real media

    escreva("Digite o nome do aluno: ")
    leia(nome)
    escreva("Digite a 1° nota: ")
    leia(nota_1)
    escreva("Digite a 2° nota: ")
    leia(nota_2)
    escreva("Digite a 3° nota: ")
    leia(nota_3)

    media = (nota_1 + nota_2 + nota_3) / 3 

    escreva(" A nota do(a) aluno(a) ", nome, " é ", media)

    // Aprendendo a forma de como realizar o cálculo de porcentagem na programção
    // Criação de variáveis 
    escreva(" Cálculo de porcentagem")
    real valor
    real porcento
    real resultado


    // Recebendo valores do usuário 
    escreva("Recebendo valores")
    escreva( " Digite o valor: ")
    leia(valor)
    escreva(" Digite o percentual: ")
    leia(porcento)

     // Cálculo da média do valor inserido pelo usuário
    escreva(" Cálculo de média do valor inserido  pelo usuário")
    resultado = valor * (porcento / 100)
    escreva(porcento, "% de ", valor, " é R$ ", resultado)

    // Cálculo de porcentagem + desconto de um produto
    escreva( " Cálculo de porcentagem + desconto de um produto")
    real valor_produto
    real valor_desconto
    real porcentagem
    real preco_final
    
    escreva(" Digite o valor do produto: ")
    leia(valor_produto)
    escreva(" Digite o porcentual do desconto: ")
    leia(porcentagem)
    
    valor_desconto = valor_produto * (porcentagem / 100)
    preco_final = valor_produto - valor_desconto
   
  
   escreva("O produto de valor R$ ", valor_produto, " com desconto de ", porcentagem, " % custa ", preco_final)
  }
}
