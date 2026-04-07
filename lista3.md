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
