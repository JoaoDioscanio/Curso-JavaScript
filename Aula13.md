# Aula 13

### 		Array / Vetor

Adicionando elementos no array:

```js
var cor = [];
cor.push = "Roxo";
// Ou
cor.unshift("Roxo")
// Ou
cor[0] = "Roxo";
```

​	push adiciona no final do array 

​	unshift adiciona no início

Removendo elementos no array:

```js
var mochila = ["Faca", "Pedra", "Chave"];
mochila.pop();
// Ou
mochila.shift();
// Ou
mochila.splice(1, 1);
```

​	pop remove o último elemento do array

​	shift remove o primeiro elemento do array

​	splice remove a quantidade que você especificar, onde o primeiro número do parênteses é a posição 	onde você quer remover e o segundo é quantos elementos quer remover a partir dessa posição

Organizando elementos do array:

```js
var mochila = ["Faca", "Pedra", "Chave"];
mochila.indexOf("Chave");
```

:arrow_right_hook: indexOf **indica** a posição de um elemento pesquisado

```js
var num = [5, 3, 1, 4, 2];
num.sort();
```

:arrow_right_hook: sort **ordena** os elementos

```js
var num = [5, 3, 1, 4, 2];
num.sort();
num.reverse();
```

:arrow_right_hook: reverse **inverte** a ordem dos elementos

```js
var num = [1, 2, 3, 4, 5, 6, 7, 8, 9];
var numeros;
numeros = num.join();
```

:arrow_right_hook: join **retorna** todos os elementos do array em uma string

```js
var mochila = [], inventario1 = ["Chave", "Pedra", "Corda"], inventario2 = ["Lanterna"];
mochila = inventario1.concat(inventario2);
```

:arrow_right_hook: concat **concatena** arrays

```js
var mochila = ["Chave", "Pedra", "Corda"], tamanho_da_mochila;
tamanho_da_mochila = mochila.lenght()
```

:arrow_right_hook: lenght **Informa** o tamanho de um array
