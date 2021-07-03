# Aula 19

### 	Declarando variáveis com let

Com o comando let, podemos declarar/alterar uma variável e deixar essa mudança apenas para o escopo onde está sendo usado

Veja esse exemplo:

```js
var num = 7;
if(num < 10){
    let num = 3;
    alert(num); // Resultado = 3
}
alert(num); // Resultado nessa situação = 7
```

