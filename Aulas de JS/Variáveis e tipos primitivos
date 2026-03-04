*Resumo da aula 5 de JS*

- tipos de variaveis que aprendemos
* window.alert() voce manda um alerta para o usuário.
* window.confirm() parece o alert porem tem a opção de confirmar ou cancelar.
* window.prompt() esse comando é uma interação com usuário.

- Comentários para lembrar
// - comentário em uma unica linha.
/* */ - comentários de mais de uma linha.

* ajustando aula 4 chama ex001.html que começamos na aula 4.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu primeiro programa</title>
    <style>
        body{background-color: rgb(131, 131, 207);
        color: rgb(244, 243, 245);
        font: normal 20pt arial;
        }
        h1{
            color: brown;
        }
    </style>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Já me livrei da maldição</p>
   <script>
        
        window.alert('Minha primeira mensagem!')
        window.confirm('Está gostando de JS?') //Janela com botão de ok e cancelar
        window.prompt('Qual seu nome?') //Vai perguntar seu nome
        
    </script>
</body>
</html>

* Simbolos de comentátio // ou /* */ só funcionan dentro do <script></script>.
* Se usar // ou /* */ após o comando não altera nada do comando.
* sinal de = no JS significa receber.

- Dentro de uma linha de comando voce sempre vai precisar usar uma variável, para atribuir um valor ou número,nome , idade,sexo.
* Simbolo da variável é var.
* variáveis com "" aspas duplas, '' aspas simples, `` crase.

- Regras basicas das variáveis
* Podem começar com letras,$ ou _
* Não podem começar com numeros
* É possivel usar letras e numeros
* É possivel usar acentos e símbolos
* Não podem conter espaço
* Não podem ser palavras reservadas
explicação: palavras reservadar são palavras que o JS usa como comando 
ex: alert,var. 

*Vamos para o Node.js dar uma brincada*

1º passo dentro do Node.js

> 3 + 7
10
> var nome = "Guilherme"
undefined
> nome
'Guilherme'
> 'nome'
'nome'
> nome
'Guilherme'
> nome = 'Darlan'
'Darlan'
> nome
'Darlan'
>.exit

* Fiz primeiro uma conta de soma depois criei uma variável nome "Guilherme"
depois substitui a variavel nome "Guilherme" para variavel 'Darlan'

2º passo abrir o Node.js dentro do proprio Vscode na parte de terminal

PS C:\Users\Eu\Documents\GitHub\Meus Projetos\Artigos de estudos> nodedos> node
Welcome to Node.js v24.14.0.
Type ".help" for more information.
> var idade = 30
undefined
> var salário = 1250.50
undefined
> var sexo = "M"
undefined
> idade
30
> salário
1250.5
> sexo
'M'
>.exit

- mais uma brincadinha

PS C:\Users\Eu\Documents\GitHub\Meus Projetos\Artigos de estudos> node
Welcome to Node.js v24.14.0.
Type ".help" for more information.
> var n1 = 12
undefined
> var n2 = 5
undefined
> n1
12
> n2
5
> n1 + n2
17
>.exit

*CTRL + L limpa a tela do terminal do vscode ou do node.js*

* Dicas para nomes de indentificadores

1º - Letras maiúsculas e minúsculas fazem diferença
ex:
> var a = 20
undefined
> var A = 40
undefined
> a
20
> A
40
> var b = 30
undefined
> B
Uncaught ReferenceError: B is not defined

2º - Escolha nomes coerentes para suas variáveis
ex:
var nome = "nome"
var idade = "idade"
var salário = "salário"

ex de não usar:
n1 = "nome"
n2 = "idade"
n3 = "salário"

3º - Evite se tornar um 'programador alfabeto' ou um 'programador contador'
ex de 'programador alfabeto'
var a = 'nome'
var b = 'idade'
var c = 'salário'
ex de 'programador contador'
var n1 = 'nome'
var n2 = 'idade'
var n3 = 'salário'

- Tipo Primitivos Primordiais

* Number - números inteiros ou números reais
ex: 5 , 7 , 100
ex: 3.14 , 0.5 , 6.75

* String - uma string (ou cadeia de caracteres) é um tipo de dado primitivo na programação usado para representar texto
ex: nome , cpf , seu número de telefone.

*ue mais cpf e número do telefone não entram nos Number por serem numeros?*
não entram porque são um conjunto de caracteres formados de números , traços e pontos.

* Boolean - significado de falso ou verdadeiro
ex: false ou true

- Esses não são os unicos tipos primitivos primordiais dentro do JS
* Number tem mais 2 valores internos que são importantes, Infinity e NaN
* null
* underfined
* object , dentro ainda existe vetores
* function
E para mexer com todos esses tipos usamos o comando 'typeof'

ex: dentro do node.js
> var n = 5000
undefined
> n
5000
> typeof n
'number'
> n = "Google"
'Google'
> typeof n
'string'
> typeof 6
'number'
> typeof 9.6
'number'
> typeof "5.5"
'string'
> typeof []
'object'
> typeof {}
'object'
> typeof function (){}
'function'
> typeof undefined
'undefined'
> typeof NaN
'number'
> typeof Infinity
'number'
> typeof null
'object'
>