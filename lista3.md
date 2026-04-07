```js
algoritmo "Atividade 1"


var
  idade:inteiro
contador:inteiro  
maiorais:inteiro  
inicio
contador<-0
maiorais<-0
 
enquanto contador<10 faca
 escreval("Digite a idade de 10 pessoas  ")
  leia(idade)
  se  idade>18 entao
  maiorais<-maiorais+1


  fimse
  contador<-contador+1
fimenquanto
escreval("quantidade de pessoas maiores de 18 ",maiorais)


fimalgoritmo
```
```js
algoritmo "Atividade 2"


var
  idade:inteiro
  contador:inteiro
  maiorais:inteiro
  maiorais1:inteiro
  maiorais2:inteiro
  maiorais3:inteiro
  maiorais4:inteiro
inicio
  contador<-0
  maiorais<-0
  maiorais1<-0
  maiorais2<-0
  maiorais3<-0
  maiorais4<-0
  enquanto contador<=15 faca
    escreval("Digite a idade de 15 pessoas  ")
    leia(idade)
    se  idade=15 entao
      maiorais<-maiorais+1
    senao se idade<30 entao
      maiorais1<-maiorais1+1
    senao se idade<45 entao
      maiorais2<-maiorais2+1
    senao se idade<60 entao
      maiorais3<-maiorais3+1
    senao se idade>=61 entao
      maiorais4<-maiorais4+1
    fimse
  fimse
fimse
fimse
fimse
contador<-contador+1


fimenquanto
escreval("menores que 15 ", maiorais )
escreval(" 16 a 30 anos.",maiorais1)
escreval("entre 31 a 45 "maiorais2)
escreval("entre 46 a 60 ", maiorais3)
escreval("maiores que 61 ",maiorais4)
fimalgoritmo
```
```js
algoritmo "Atividade3"

var
  voto: inteiro
  i: inteiro
  c1, c2, c3, c4: inteiro
  nulo, branco: inteiro

inicio
  c1 <- 0
  c2 <- 0
  c3 <- 0
  c4 <- 0
  nulo <- 0
  branco <- 0

  para i de 1 ate 10 faca
    escreva("Digite o voto (1-6): ")
    leia(voto)

    escolha voto
      caso 1
        c1 <- c1 + 1
      caso 2
        c2 <- c2 + 1
      caso 3
        c3 <- c3 + 1
      caso 4
        c4 <- c4 + 1
      caso 5
        nulo <- nulo + 1
      caso 6
        branco <- branco + 1
    fimescolha
  fimpara

  escreval("Candidato 1: ", c1)
  escreval("Candidato 2: ", c2)
  escreval("Candidato 3: ", c3)
  escreval("Candidato 4: ", c4)
  escreval("Votos nulos: ", nulo)
  escreval("Votos em branco: ", branco)

fimalgoritmo
```
```js
algoritmo "Atividade 4"

var
   contador: inteiro
   sexo: caractere
   altura, maior, menor, somaMulheres, mediaMulheres: real
   qtdHomens, qtdMulheres: inteiro

inicio
   maior <- 0
   menor <- 0
   somaMulheres <- 0
   qtdHomens <- 0
   qtdMulheres <- 0

   para contador de 1 ate 15 faca
      escreva("Digite a altura: ")
      leia(altura)

      escreva("Digite o sexo (M/F): ")
      leia(sexo)

    
      se contador = 1 entao
         maior <- altura
         menor <- altura
      senao
         se altura > maior entao
            maior <- altura
         fimse

         se altura < menor entao
            menor <- altura
         fimse
      fimse

    
      se sexo = "M" ou sexo = "m" entao
         qtdHomens <- qtdHomens + 1
      fimse

    
      se sexo = "F" ou sexo = "f" entao
         somaMulheres <- somaMulheres + altura
         qtdMulheres <- qtdMulheres + 1
      fimse

   fimpara

  
   se qtdMulheres > 0 entao
      mediaMulheres <- somaMulheres / qtdMulheres
   senao
      mediaMulheres <- 0
   fimse

   escreval("Número de homens: ", qtdHomens)
   escreval("Maior altura: ", maior)
   escreval("Menor altura: ", menor)
   escreval("Média das mulheres: ", mediaMulheres)

fimalgoritmo
```
```js
algoritmo "Atividade 5"

var
   f, c: real

inicio
   f <- 50

   escreval("Fahrenheit   Centigrados")

   enquanto f <= 65 faca
      c <- 5/9 * (f - 32)
      escreval(f:5:1, "        ", c:6:2)
      f <- f + 1
   fimenquanto

fimalgoritmo
```
```js
algoritmo "Atividade 6 /A"

var
   numero: inteiro
   soma: real

inicio
   soma <- 0

   para numero de 1 ate 10 faca
      soma <- soma + (numero / (numero * numero))
   fimpara

   escreval("Resultado da sequência A: ", soma)

fimalgoritmo

algoritmo "Atividade 6/B"

var
   numero :inteiro
   soma: real

inicio
   soma <- 0

   para numero de 1 ate 50 faca
      soma <- soma + ((2 * numero - 1) / numero)
   fimpara

   escreval("Resultado da sequência B: ", soma)

fimalgoritmo

```
```js
algoritmo "Atividade 7"

var
  ok: inteiro
  a, b, c: inteiro

inicio
  a <- 0
  b <- 1

  escreva(a, " ", b, " ")

  para ok de 3 ate 11 faca
    c <- a + b
    escreva(c, " ")
    a <- b
    b <- c
  fimpara

fimalgoritmo
```