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