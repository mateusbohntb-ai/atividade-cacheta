# atividade-cacheta
```js
``1 atividade``
algoritmo "Atividade 1"

var 
 raio : real
 resultado : real

 inicio 

 escreval("Digite o raio?")
 leia(raio)

 resultado <- raio *2 * 3.14159
 escreval("resultado: ", resultado )

 fimalgoritmo
```
 ......................................................................................................................................... 
 ```js
 ``atividade 2``
 bash algoritmo"atividade2"

var
peso:real
altura:real
imc:real

inicio
escreval("digite altura")
leia(altura)
escreval("digite um peso")
leia(peso)

imc <- peso/(altura*altura)
escreval("resultado:",imc)

 fimalgoritmo
 ```
.........................................................................................................................................................................
```js
```Atividade 3```
algoritmo "Atividade 3"

var
   variavel1:caracter
   variavel2:caracter
 auciliar:caracter

inicio

   escreval("Digite um nome :")
   leia(variavel1)
   escreval("digite outro nome:")
     leia(variavel2)
auciliar<-variavel1
variavel1<-variavel2
variavel2<-auciliar
escreval("variavel1: ",variavel1)
escreval("variavel2: ",variavel2)
fimalgoritmo
perdao sor nao salvou no vscode 
```
...........................................................................................................................................................................

```js
```Atividade 4```
algoritmo"atividade4"
var
  numero:real


inicio
  escreval("Digite um numero")
  leia(numero)
  se ( numero > 0 ) entao
    escreval("esse numero é positivo")
  senao
    se (numero < 0)  entao
      escreval("esse numero é negativo")
    senao
      escreva("zero")
    fimse
  fimse

fimalgoritmo
```

...............................................................................
```js
algoritmo"Atividade 5"
var
  salario,salario2:real


inicio
  escreval("Digite seu sálario")
  leia(salario)

  se ( salario <= 1.500 ) entao
    salario2 <- salario*1.15
   
  senao
 
    salario2 <- salario*1.10
    
  fimse

escreval("novo salario é: R$ " , salario2)
fimalgoritmo
```
....................................................................................
```js
algoritmo "Atividade 6"

var
  ano: inteiro
resto:inteiro
inicio

  escreval("Digite um ano : ")
  leia(ano)
  

resto <-  ano mod 400
se (resto = 0)entao
escreval( ano ," é um ano bixesto ")
senao 
escreval(ano ,"nao é um ano bixesto ")
fimse
fimalgoritmo
```
.......................................................................................................
```js
algoritmo "Atividade 7"

var

   numero: inteiro
   resto: inteiro

inicio
   escreva("Digite um número entre 0 e 10: ")
   leia(numero)

   resto <- 1

   para numero de 1 ate numero faca
     resto<-resto * numero
   fimpara

   escreval("Fatorial de ", numero, " = ",resto)

fimalgoritmo
```
...................................................................................................
```js
algoritmo "Atividade 8"

var
  numero: inteiro
  computador:inteiro
  resto: inteiro
  sair: logico
inicio

  escreval("Digite um numero: ")
  leia(numero)



  se (numero>1)entao
    computador <-2
    sair <- falso
    enquanto computador < numero e sair = falso faca
      resto <- numero mod computador
      se resto = 0 entao
        escreva("não é primo")
        sair <- verdadeiro
      fimse
      computador <-computador+1
    fimenquanto

    se sair = falso entao
      escreva("é primo")
    fimse
  senao
    escreval("não é possivel calcular")


  fimse
fimalgoritmo
``
..................................................................................................................................................
```js
`Algoritmo "Atividade 9"

Var
  numero_secreto:inteiro
   palpite:inteiro
   tentativa: inteiro

Inicio
  
  
  numero_secreto <- 42

  Para tentativa de 1 ate 5 faca
    Escreva("Tentativa ", tentativa, ": Digite seu palpite: ")
    Leia(palpite)

    Se palpite = numero_secreto entao
      Escreva("Parabéns! Você acertou em ", tentativa, " tentativa(s).")

    Senao
      Se palpite < numero_secreto entao
        Escreva("Maior")
      Senao
        Escreva("Menor")
      FimSe
    FimSe
  FimPara

  Se palpite <> numero_secreto entao
    Escreva("Que pena! Você não acertou o número secreto.")
  FimSe

Fimalgoritmo
```