---
layout: post
published: false
title: Como utilizar o protocolo ESC/POS
---
## O que é o [ESC/POS](https://en.wikipedia.org/wiki/ESC/P)?
É um protocolo de comunicação com impressoras do tipo Point of Sale (POS) criado pela Epson e utilizado por diversos modelos e marcas de impressoras. Ele permite que sejam utilizados sequencias de comandos para que a impressora realize alguma ação, como imprimir em negrito ou sublinhado.  
Possui como característica iniciar a sequencia de comandos com o caractere **ESC** (Decimal 27) e utilizar outros caracteres da tabela [ASCII](https://pt.wikipedia.org/wiki/ASCII) para completar o comando, por exemplo:  
~~~
ESC E (Em caractere)
27 69 (Em decimal)
1B 45 (Em hexadecimal)
~~~


### Tabela ASCII
Todos os comandos desse protocolo são baseados nos caracteres da tabela ASCII e podem ser utilizados tanto na forma de caractere como na forma decimal ou hexadecimal, portanto é interessante sempre manter uma por perto para que seja consultada.


## Comandos ESC/POS
