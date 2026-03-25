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

```js
algoritmo "Primeiro Programa"

var
  valor1:caracter
  valor3:inteiro


inicio

  escreval(" Digite sua forma de pagamento  ")
  leia(valor1)
se valor1 ="cartão" entao
valor3<- valor1 *0.05
escreval("Seu desconto total no cheque  será ", valor3)
senao se valor1 ="cheque " entao
valor3<-valor1*0.1
escreva("Seu desconto total no cartão",valor3)
senao se valor1 ="duas vezes " entao
escreval("Seu preço sera normal de etiqueta sem juros ")
senao se valor1="tres vezes" entao 
valor3<-valor1*0.1
escreval("Seu desconto em trez vezes sera ", valor3)
fimse
fimse
fimse
fimse
fimalgoritmo
