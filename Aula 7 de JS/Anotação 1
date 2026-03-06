*Resumos da aula 7 de JavaScript*

- Na aula 7 do curso de JS vamo falar sobre operadores
* Aritimético
* Atribuição
* Relacionais
* Logicos
* Ternário

- Aritiméticos
* (+) Adição
* (-) Subtração
* (*) Multiplicação
* (/) Divisão
* (%) Porcentagem
* (**) Potenciação
ex:

5 (+) 2 = 7
5 (-) 2 = 3
5 (*) 2 = 10
5 (/) 2 = 2.5
5 (%) 2 = 1
5 (**) 2 = 25

**CUIDADO!!**
- cuidado com a precedencia de operadores
ex:
5 (+) 3 (/) 2 = 6.5 eu respodi 4 erradão

vamos fazer alguns terinos no node.js
> 5 + 2
7
> 9 % 2
1
> 9 / 2
4.5
> 5 + 3 / 2
6.5
> 5 + / 2
5 + / 2
    ^

Uncaught SyntaxError: Invalid regular expression: missing /
ex:

> 5 + 3 / 2
6.5
> (5 + 3) / 2
4

- Ordem de Precedência
1º - () -> primeiro tudo em parenteses primeiro
2º - (**) -> as potencias
3º - (*)(/)(%) -> multiplicação,divisão e resto da divisão
4º - (+)(-) -> adição e subtração

ex:
var a = 5 + 3 = 8
var b = a % 5 = 3
var c = 5* b**2 = 45
var d = 10 - a / 2 = 6
var e = 6 * 2 / d = 2 
var f = b % e + 4 / e = 3

- Auto atribuição

var n = 3

n = n + 4 = 7   -> N passa a valer 7
n = n - 5 = 2   -> N passa a valer 2
n = n * 4 = 8   -> N passa a valer 8
n = n / 2 = 4   -> N passa a valer 4
n = n ** 2 = 16 -> N passa a valer 16
N = n % 5 = 1   -> N passa a valer 1

- Simplificando auto atribuição

* A simplificação só acontece quando a variavel recebe ela mesma

n = n + 4 =  simplificado  n + = 4
n = n - 5 =  simplificado  n - = 5
n = n * 4 =  simplificado  n * = 4
n = n / 2 =  simplificado  n / = 2
n = n ** 2 = simplificado  n ** = 2
n = n % 5 =  simplificado  n % = 5

Ex no node.js:

> var num = 8
undefined
> num
8
> num += 2
10
> num
10
> num %= 2
0
> var num = 3
undefined
> num
3
> num **= 2
9

- Operadores de Incremento

var x = 5

x = x + 1 = 6  incremento x++
x = x - 1 = 5  incremento x--

ex no node.js

> var n = 10
undefined
> n
10
> n++
10
> n
11
> n--
11
> n
10
> n
10
> ++n
11
> --n
10
>
