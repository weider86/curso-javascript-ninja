# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function twoArg(x, y){
    var soma = x + y;
    return soma;
  }    

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var join =  twoArg(1, 2) + 5;

// Qual o valor atualizado dessa variável?
8

// Declare uma nova variável, sem valor.
var noVal;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function nuFun(){
 noVal == 10;
 var resposta = "O valor da variável agora é " + noVal;
 return resposta
}

// Invoque a função criada acima.
nuFun()

// Qual o retorno da função? (Use comentários de bloco).
/*
O valor da variável agora é 10
*/

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/

function treeArgs(x, y, z){

  if(x === undefined || y === undefined || z === undefined){
      var resposta = 'Preencha todos os valores corretamente!'
      return 'Preencha todos os valores corretamente!'
  } 
  else{
    var mult = x * y * z;
    var soma = mult + 2
    return soma;
  }

}

?

// Invoque a função criada acima, passando só dois números como argumento.
treeArgs(1, 2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
//"Preencha todos os valores corretamente!"

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
treeArgs(1, 2, 3);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
8

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function treeArg(x, y, z){  
  
  if(x === undefined && y === undefined && z === undefined){
    return false
  } 
  else if(y === undefined && z === undefined ){
    var valor = x;
    return valor;
  } 
  else if(z === undefined){
    var soma = x + y;
    return soma;
  }    
  else if(x !== undefined && y !== undefined && z !== undefined){
     var soma2 = x + y;
     var divi = soma2 / z
     return divi;
  }
  else{
    return null
  } 
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
treeArg(); //false
treeArg(2); //2
treeArg(8,1); //9
treeArg(3, 2, 2); //2.5
```
