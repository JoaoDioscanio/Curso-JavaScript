# Aula 3

###   Constantes

São parecidas com variáveis (armazenam informações na memória) **porém** não podem ser alteradas

Utiliza-se o comando const + informação para definir constantes

Veja a diferença de um comando errado em um código:

```html
var canal = "CFB Cursos"
canal = "JavaScript"
document.write(canal)
```

​                                                         							 :arrow_down: 

​											Resultado = Último valor mostrado (no caso "Java Script")

```html
const canal = "CFB Cursos"
canal = "JavaScript"
document.write(canal)
```

​														 						    :arrow_down:

​											  						   Resultado = Erro

Por isso não tente mudar o valor de uma constante

