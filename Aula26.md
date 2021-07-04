# Aula 26

### 	Trabalhando com data e hora

| Método            | Descrição                                     | Exemplo                                   |
| ----------------- | --------------------------------------------- | ----------------------------------------- |
| getDay();         | Retorna o dia da semana, domingo=0, segunda=1 | var diaSem=data.getDay();                 |
| getDate();        | Retorna o dia do mês                          | var dia=data.getDate();                   |
| getMonth();       | Retorna o mês, janeiro=0, fevereiro=1         | var mes=data.getMonth();                  |
| getFullYear();    | Retorna o ano com 4 dígitos, ex: 2015         | var ano=data.getFullYear();               |
| getHours();       | Retorna a hora                                | var hora=data.getHours();                 |
| getMinutes();     | Retorna os minutos                            | var minutos=data.getMinutes();            |
| getSeconds();     | Retorna os segundos                           | var segundos=data.getSeconds();           |
| toDateString();   | Retorna a data por estêncil, padrão EUA       | var dataTexto=data.toDateString();        |
| toDateString();   | Retorna a data no formato 16/12/2015          | var dataPadrao=data.toLocaleDateString(); |
| toLocaleString(); | Retorna a data e a hora 16/12/2015 23:13:00   | var dataHoraTexto=data.toLocaleString();  |

**Lembre-se!**

O computador começa a contar do zero

Exemplo: Janeiro = 0 Fevereiro = 1 Março = 2 Abril = 3

