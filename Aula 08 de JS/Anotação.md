*Resumo aula 8 curso de JS*

* Operadores relacionais

- 5 > 2 = true
- 7 < 4 = false
- 8 >= 8 = true
- 9 <= 7 = false
- 5 == 5 = true
- 4 != 4 = false

ex no node.JS

> 5 > 2
true
> 8 < 4
false
> var a = 8
undefined
> var b = 15
undefined
> a > b
false
> a < b
true
> a <= b - 10
false
> a == b
false
> a != b
true
>

- Operadores relacionais de indentidade

* operador de igualdade restrita -> === *

- 5 == 5 = true
- 5 == '5' = true -> mesmo o '5' em string
- 5 === '5' = false
- 5 === 5 = true
ex no node.JS

> 5 == '5'
true
> var x = 5
undefined
> var y = '5'
undefined
> typeof x
'number'
> typeof y
'string'
> x == y
true
> x === y
false
> x != y
false
> x !== y
true
>

* Operadores lógicos

- ! significa negação
- && significa conjunção
- || significa disjunção

*importate*
quando voce tem operadores aritiméticos , relacionais e logicos na mesma expressão a ordem é o seguinte 
1º todos os operadores aritiméticos
2º todos os operadores relacionais
3º todos os operadores lógicos

ex no node.JS
> var a = 5
undefined
> var b = 8
undefined
> true && false
false
> true && true
true
> false || false
false
> true || false
true
> true || true
true
> a > b && b % 2 == 0
false
> a <= b || b / 2 == 2
true
>

* Importante ordem de precedência

Sempre seguir essa ordem de precedência nas operações :

- 1º operadores aritiméticos 
ex: () , (**) , (/) (*) 
- 2º operadores relacionais, ordem de quem aparecer primeiro
ex: (>) , (<) , (>=)
- 3º operadores lógicos tem uma ordem de precedencia
1 - (!) -> não
2 - (&&) -> e
3 - (||) -> ou

* Operadores ternários 

- Operadores ternários é a (?) e (:) dentro da mesma expressão
- ele se chama ternário porque tem 3 partes
ex:
- teste (?) true (:) False
ex -> o que vai acontecer se o teste for verdadeiro e o que vai acontecer se o teste for falso

ex no node.JS

> var média = 5.5
undefined
> média > 7? 'APROVADO' : 'REPROVADO'
'REPROVADO'
> média += 3
8.5
> média
8.5
> média > 7? 'APROVADO' : 'REPROVADO'
'APROVADO'

ex:
> var x = 8
undefined
> var res = x % 2 == 0 ? 5 : 9
undefined
> x
8
> res
5
> var idade = 19
undefined
> var r = idade >= 18 ? 'MAIOR' : 'MENOR'
undefined
> r
'MAIOR'
>