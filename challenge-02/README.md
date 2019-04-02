# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma(a, b) {
return a + b;
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var mysum = soma( 7, 2) + 8;

// Qual o valor atualizado dessa variável?
17

// Declare uma nova variável, sem valor.
var newnum;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function addvalor(){
newnum = 12;
return 'O valor da variável agora é ' + newnum; 
}

// Invoque a função criada acima.
addvalor();

// Qual o retorno da função? (Use comentários de bloco).
*/
"O valor da variável agora é 12"
*/
<<<<<<< HEAD

=======
>>>>>>> 05d44e00fd0aa5148a0be19fd20344bff9188fc7

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function operacoes( a, b, c) {
  if ( a === undefined || b === undefined || c === undefined) {
     return '  Preencha todos os valores corretamente! ';
  } else{
     return (a * b * c) + 2; 
  }
}
<<<<<<< HEAD
=======

>>>>>>> 05d44e00fd0aa5148a0be19fd20344bff9188fc7

// Invoque a função criada acima, passando só dois números como argumento.
operacoes( 5, 3);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// "  Preencha todos os valores corretamente! "

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
operacoes(5, 3, 2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// 32

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function complex(a, b, c){
 if(a !== undefined && b === undefined && c === undefined ){
   return a;
 } else if( a !== undefined && b !== undefined && c === undefined ){
     return a + b;
 }else if( a !== undefined && b !== undefined && c !== undefined ){
     return (a + b) / c;
 } else if ( a === undefined || b === undefined || c === undefined) {
    return 'False';
 } else{
    return null; 
  }
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
<<<<<<< HEAD
=======
?
>>>>>>> 05d44e00fd0aa5148a0be19fd20344bff9188fc7
/* complex()
"False"
*/

/* 
complex(2)
2
*/

/*
complex(2,4)
6
*/

/*
complex(2, 4, 2)
3
*/
<<<<<<< HEAD
```
=======
>>>>>>> 05d44e00fd0aa5148a0be19fd20344bff9188fc7
