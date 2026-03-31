## lista 2
```js 
algoritmo "Primeiro Programa"

var
  dadaNacimento: inteiro
  anoatual:inteiro
  resto:inteiro
inicio

  escreval("Digite o ano que você naceu  : ")
  leia(dadaNacimento)

  anoatual <-2026
  resto<-anoatual-dadaNacimento
  escreval("sua idade ",resto)
  se resto>18  entao
    escreval("Você  possui idade suficiente para votar e  dirigir ")
  senao
    escreval("Você não pode votar e dirigir ")
  FimSe

fimalgoritmo
```
.....................................................................................................
```js
algoritmo "Atividade 2 "

var
  numero1: inteiro
  numero2:inteiro
  operacao:caracter
  resultado:inteiro
inicio
  escreval("Digite operação matematica ")
  leia(operacao)
  escreval("Digite o ano que você naceu  : ")
  leia(numero1)
  escreval("Digite o ano que você naceu  : ")
  leia(numero2)
  se operacao="+"  entao
    resultado<-numero1+numero2
    escreval("A sua soma é ",resultado)
  senao
    se operacao = "-" entao
      resultado<- numero1-numero2
      escreval("a sua subtração é "operacao)
    senao
      se operacao ="/" entao
        resultado<- numero1/numero2
        escreval("sua divisão é "resultado)
      senao
        se operacao ="x" entao
          resultado<- numero1/numero2
          escreval("sua divisão é "resultado)
          operacao
        FimSe
      FimSe
    FimSe
  FimSe
fimalgoritmo
```

...........................................................................................................
```js
algoritmo "Atividade 3"

var
  altura: inteiro
  peso:inteiro
  IMC:real
inicio

  escreval("Digite sua altura   : ")
  leia(altura)
  escreval("Digite o seu peso : ")
  leia(peso)

  IMC<- peso/(altura*altura)

  escreval("IMC ", IMC)

  se IMC<18.5 entao
    escreval("Você está abaixo do peso ")
    
  senao
  se IMC >= 18.5 e IMC <25 entao
    escreval("seu peso esta normal")
    
  senao se IMC >=25 e IMC<30 entao
    escreval("Você está acima do peso ")
    
  senao se IMC >30 entao
    escreval("você esta obeso")
  fimse
fimse
fimse
fimse
fimalgorit
```
...............................................................................................................................................
```js
algoritmo "Atividade 4"

var
  valor1:caracter
  preco:inteiro 
valor3:inteiro


inicio

  escreval(" Digite sua forma de pagamento ")
  leia(valor1)
 escreval(" Digite o preço do produto  ")
  leia(preco)

se valor1 ="cartão" entao
valor3<- preco *0.05
escreval("Seu desconto total no cartão será ", valor3)

senao se valor1 ="cheque " entao
valor3<-preco*0.1
escreva("Seu desconto total no cheque ",valor3)

senao se valor1 ="duas vezes " entao
escreval("Seu preço sera normal de etiqueta sem juros ")

senao se valor1="tres vezes" entao 
valor3<-preco*0.1
escreval("Seu desconto em trez vezes sera ", valor3)
fimse
fimse
fimse
fimse
fimalgoritmo
```
................................................................................................................

```js
algoritmo "Atividade 5"

var
  idade:inteiro


inicio
  escreval("Digite sua idade")
  leia(idade)

  se idade<=7 entao
    escreva(" você é uma criança")

  senao se (idade<=10)  entao
    escreval("você é infantil B")

  senao se  idade<=13 entao
    escreva("Você é juvenil A")

  senao se  idade <=17 entao
    escreva("Você é juvnil B ")

  senao se  idade>18   entao
    escreva ("Voc é adulto ")
  fimse
fimse
fimse
fimse
fimse
fimalgoritmo
```
...............................................................................................................
```js
algoritmo "Atividade 6"

var
  investimento:caracter
  valor2:inteiro
  valor:inteiro
inicio
  escreval("Digite seu tipo de investimento ")
  leia(investimento)

  escreval("Digite seu tipo de investimento ")
  leia(valor2)
  se investimento="po" entao
    valor <-valor2+(valor2*0.03)
    escreval("Seu valor de investimento de pupança " ,valor)

  senao se investimento="renda fixa" entao
    valor <-valor2+(valor2*0.04)
    escreval("seu valor de renda fixa e de " , valor)
  fimse 
fimse
fimalgoritmo
```
....................................................................................................................................................................
```js
algoritmo "Atividade 7"

var

  peso:real
  idade:real
inicio
  escreval("Digite seu peso ")
  leia(peso)
  escreval("Digite sua idade ")
  leia(idade)

  se peso<60 e idade<20  entao
    escreval("sua classificação é 9")
  senao se  peso<90 e idade<20 entao
    escreval("Sua classificação é de 8")
  senao se peso>90 e idade<20 entao
    escreval("S ua classificação é de 7")
  senao se peso<60 e idade<=50 entao
    escreval("Sua classificação é de 6 ")
  senao  se peso<90 e idade<=50 entao
    escreval("Sua classificação é de 5 ")
  senao  se peso>90 e idade<=50 entao
    escreval("Sua classificação é de 4 ")
  senao  se peso<60 e idade>50 entao
    escreval("Sua classificação é de 3")
  senao  se peso<90 e idade>50 entao
    escreval("Sua classificação é de 5 ")
  senao  se peso>90 e idade>50 entao
    escreval("Sua classificação é de 5 ")
  fimse
fimse
fimse
fimse
fimse
fimse
fimse
fimse
```
..........................................................................
```js
algoritmo "Atividade 8"

var

  salario:inteiro
resto:inteiro
inicio
  escreval("Seu salario")
  leia (salario)
  se salario <300 entao 
resto<- salario+(salario*0.35)
escreval("seu salario é " ,resto )
senao se salario>300 entao 
resto <- salario+(salario*0.15)
escreval("salario final é " , resto )
fimse 
fimse 
fimalgoritmo
```
..........................................................................................................
```js
algoritmo "Atividade 9"

var
   n1, n2, resultado: real
   opcao: inteiro

inicio

   escreva("Digite o primeiro número: ")
   leia(n1)
   escreva("Digite o segundo número: ")
   leia(n2)
   escreva("Escolha a operação (1, 2 ou 3): ")
   leia(opcao)
   se opcao = 1 entao
      resultado <- (n1 + n2) / 2
   fimse
   se opcao = 2 entao
      resultado <- n1 + n2
   fimse
   se opcao = 3 entao
      resultado <- n1 * n2
   fimse
   se opcao = 1 ou opcao = 2 ou opcao = 3 entao
      escreva("Resultado: ", resultado)
   senao
      escreva("Opção inválida")
   fimse

fimalgoritmo
```
..........................................................................................................................................
```js
algoritmo "10"

var
   salario, aumento, novo: real

inicio

   escreva("Digite o salário: ")
   leia(salario)
   se salario <= 300 entao
      aumento <- salario * 0.15
   fimse
   se salario > 300 e salario <= 600 entao
      aumento <- salario * 0.10
   fimse
   se salario > 600 e salario <= 900 entao
      aumento <- salario * 0.05
   fimse
   se salario > 900 entao
      aumento <- 0
   fimse
   novo <- salario + aumento
   escreva("Aumento: ", aumento)
   escreva("Novo salário: ", novo)

fimalgoritmo
```
.....................................................................................................................................................