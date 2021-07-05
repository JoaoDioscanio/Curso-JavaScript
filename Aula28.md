# Aula 28

### 	Funções

Uma ótima forma de controlar a execução de determinado bloco de código em um programa é utilizar funções, assim podemos criar toda uma rotina de programação e executar esta rotina em um momento específico, ter esse controle é extremamente útil e fundamental.  

Quando criamos uma função, adicionamos uma série de comandos dentro desta função e estes comandos somente serão executados quando a função for chamada, ou seja, se em nenhum momento a função não for chamada, os comandos não serão executados, então, eu consigo determinar o momento exato que precisamos executar estes comandos que estão no escopo (corpo) da função.

Outro detalhe importante é quanto a economia de código, suponhamos que exista um bloco de comandos que precisa ser executado várias vezes em momentos diferentes em nosso programa, ao invés de repetir este bloco de comandos várias vezes, simplesmente adicione este bloco em uma função e sempre que precisar executar este bloco de comandos, basta chamar a função.

Sintaxe:

function nome da função (parâmetro){

​	comandos

}

Exemplo:

```js
function escrever(){
    document.write("CFB Cursos")
}
```

