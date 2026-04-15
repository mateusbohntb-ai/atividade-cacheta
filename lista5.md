```js
algoritmo "Atividade 1"

var
 contador : inteiro
inicio
para contador de 30 ate 3 passo -3 faca 
escreval(contador)
fimpara 

fimalgoritmo
```
```js
 "Atividade 2"

var
   contador  : inteiro
inicio
para contador de 20 ate 1 passo -2 faca 
escreval(contador)
fimpara 

fimalgoritmo
```
```js
algoritmo "Atividade 3"

var
  resultado : inteiro
numero  ,contador : inteiro
inicio
resultado<-1
 escreval("Digite um numero")
 leia(numero)
  para contador de numero ate 1 passo -1 faca 
  resultado<-resultado*contador
  fimpara
    escreval(resultado)
fimalgoritmo
```
```js
algoritmo "Atividade 4"

var
  nota ,contador:real

inicio



  para contador de 10 ate 0 passo -1 faca 
  escreval("Digite uma Nota:")
leia(nota) 
 
    se nota <2.9 entao
      escreval("Sua nota esta abaixo da media conceito  E")
    senao se nota<4.9 entao
     escreval ("Sua nota você esta melhorando conceito  D")
    senao se nota<6.9 entao
      escreval ("Sua nota você está quase la conceito  C")
    senao se nota<8.9 entao
      escreval ("Sua nota você está na media conceito  B")
    senao se nota<=10 entao
      escreval ("Sua nota esta nota maxima conceito  A ")

fimse
fimse
fimse
fimse
fimse
contador<-contador+1
fimpara
fimalgoritmo
```
```js
algoritmo "Atividade 5"

var
  nota ,contador,quantidadeD,quantidadee,  quantidadec,    quantidadeB,    quantidadeA:real

inicio
  contador<-0
  quantidadeD<-0
  quantidadee<-0
  quantidadec<-0
  quantidadeB<-0
  quantidadeA<-0
  para contador de 10 ate 0 passo -1 faca 
  escreval("Digite sua nota : ")
   leia(nota)
    se nota <2.9 entao
     escreval("Sua nota é E")
      quantidadee<-quantidadee+1
      escreval("quantidade de E",quantidadee)
    senao se nota<4.9 entao
     escreval ("Sua nota é D")
      quantidadeD<-quantidadeD+1
        escreval("quantidade de D",quantidadeD)
    senao se nota<6.9 entao
      escreval ("Sua nota é C")
      quantidadec<-quantidadec+1
            escreval("quantidade de C",quantidadeC)
    senao se nota<8.9 entao
      escreval ("Sua nota é B")
      quantidadeB<-quantidadeB+1
        escreval("quantidade de B",quantidadeB)
    senao se nota<=10 entao
      escreval ("Sua nota é A")
      quantidadeA<-quantidadeA+1
       escreval("quantidade de A",quantidadeA)

fimse
fimse
fimse
fimse
fimse
contador<-contador+1
fimpara 
fimalgoritmo
```
```js
Obs:Esse codigo nao pode ser usado com para por conta que o codigo nao estipula um limite ou seja sem um limite nao sera possivel digitar "para "na quastao

algoritmo "Atividade 6"

var
   idade: inteiro
   peso, altura: real
   menores18, mais80kg, total: inteiro
   somaIdade, somaAltura, mediaIdade, mediaAltura: real

inicio
   menores18 <- 0
   mais80kg <- 0
   total <- 0
   somaIdade <- 0
   somaAltura <- 0

   escreva("Digite a idade (0 para encerrar): ")
   leia(idade)

   enquanto idade <> 0 faca
      
      escreva("Digite o peso: ")
      leia(peso)
      
      escreva("Digite a altura: ")
      leia(altura)

      total <- total + 1
      somaIdade <- somaIdade + idade
      somaAltura <- somaAltura + altura

      se idade < 18 entao
         menores18 <- menores18 + 1
      fimse

      se peso > 80 entao
         mais80kg <- mais80kg + 1
      fimse

      escreva("Digite a idade (0 para encerrar): ")
      leia(idade)

   fimenquanto

   se total > 0 entao
      mediaIdade <- somaIdade / total
      mediaAltura <- somaAltura / total
   senao
      mediaIdade <- 0
      mediaAltura <- 0
   fimse

   escreval("Menores de 18: ", menores18)
   escreval("Media das idades: ", mediaIdade)
   escreval("Media das alturas: ", mediaAltura)
   escreval("Mais de 80kg: ", mais80kg)

fimalgoritmo
```
```js
Obs:Esse codigo nao pode ser usado com para por conta que o codigo nao estipula um limite ou seja sem um limite nao sera possivel digitar "para "na quastao

algoritmo "Atividade 7"

var
   codigo, veiculos, acidentes: inteiro
   totalCidades, contMenos2000: inteiro
   somaVeiculos: inteiro
   somaAcidentesMenos2000: inteiro
   mediaVeiculos, mediaAcidentes, indice, maiorIndice: real

inicio
   totalCidades <- 0
   somaVeiculos <- 0
   somaAcidentesMenos2000 <- 0
   contMenos2000 <- 0
   maiorIndice <- 0

   escreva("Digite o codigo da cidade (0 para encerrar): ")
   leia(codigo)

   enquanto codigo <> 0 faca

      escreva("Numero de veiculos: ")
      leia(veiculos)

      escreva("Numero de acidentes: ")
      leia(acidentes)

      totalCidades <- totalCidades + 1
      somaVeiculos <- somaVeiculos + veiculos

      indice <- acidentes / veiculos

      se indice > maiorIndice entao
         maiorIndice <- indice
      fimse

      se veiculos < 2000 entao
         somaAcidentesMenos2000 <- somaAcidentesMenos2000 + acidentes
         contMenos2000 <- contMenos2000 + 1
      fimse

      escreva("Digite o codigo da cidade (0 para encerrar): ")
      leia(codigo)

   fimenquanto

   se totalCidades > 0 entao
      mediaVeiculos <- somaVeiculos / totalCidades
   senao
      mediaVeiculos <- 0
   fimse

   se contMenos2000 > 0 entao
      mediaAcidentes <- somaAcidentesMenos2000 / contMenos2000
   senao
      mediaAcidentes <- 0
   fimse

   escreval("Maior indice de acidentes: ", maiorIndice)
   escreval("Media de veiculos: ", mediaVeiculos)
   escreval("Media de acidentes (<2000 veiculos): ", mediaAcidentes)

fimalgoritmo
```