*Resumo da aula 6 de JS*

- Na aula 4 de JavaScrit aprendemos o prompt, porém nao armazenava os dado e nessa aula vamos aprende a manipular dados.

* Comentarios em cada tecnologia

- em JS // ou /* */ .
- em HTML <!--Digite aqui-->
- em CSS /* */ .
- sinal de + tem 2 significador dependendo do seu comendo, para adição e concatenação
- window.prompt recebe sempre valor em String

* Conversão de String para Number
- Number.parseInt(n) para números inteiros
ex: 1 , 5 , 10 , 1000
- Number.parseFloat(n) pra números reais
ex: 2.5 , 3.14 , 5.5
- Number(n) modo simplificado do JS , voce coloca os valores e ele faz a conversão de números inteiros ou reais.

* Conversão de Number para String
- String(n)
- n.toString()

* Formatando Strings
var s = 'JavaScript'
- 'Eu estou estudando s' // não faz interpolação
- 'Eu estou estudando' + s // usa concatenação
- `Eu estou estudando ${s}` // usa template string

- Vamos criar um exemplo usando o node.js
ex simples: 'Eu estou estudando s'

> var s = 'JavaScript'
undefined
> s
'JavaScript'
> 'Eu estou estudando s'
'Eu estou estudando s'
> 'Eu estou estudando ' + s
'Eu estou estudando JavaScript'

ex de concatenação 'Eu estou aprendendo' + s

> var nome = 'Leandro'
undefined
> var idade = 32
undefined
> var nota = 10
undefined
> nome
'Leandro'
> idade
32
> nota
10
> 'O aluno ' + nome + ' com ' + idade + ' anos tirou a nota ' + nota
'O aluno Leandro com 32 anos tirou a nota 10'

ex de tempate string `Eu estou aprendendo ${s}`

> var nome = 'Leandro'
undefined
> var idade = 32
undefined
> var nota = 10
undefined
> nome
'Leandro'
> idade
32
> nota
10
> `O aluno ${nome} com ${idade} anos tirou a nota ${nota}`
'O aluno Leandro com 32 anos tirou a nota 10'

* Formatos de Strings
var s = 'JavaScript'
- s.lenght // quantos caracteres a string tem
- s.toUpperCase() // tudo para 'MAIÚSCULAS'
- s.toLoweCase() // tudo para 'minúsculas'
ex: ex004.html

* Formatando Números
var n1 = 1543.5
- n1
- n1.toFixed(2)
- n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})

ex no node.js

> var n1 = 1545.5
undefined
> n1
1545.5
> n1.toFixed(2)
'1545.50'
> n1.toFixed(2).replace('.', ',') // trocar o ponto por virgula
'1545,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) //valor em reais 
'R$ 1.545,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'USD'}) // valor em dolar
'US$ 1.545,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'EUR'}) // valor em euro
'€ 1.545,50'