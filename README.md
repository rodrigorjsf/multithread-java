# multithread-java
Repositório direcionado ao estudo de multithread em Java


## Paralelismo

- Capacidade de executar vários techos de código no mesmo instante. Apenas possível em cenários onde o processador tem mais de um núcleo.

## Concorência

- Várias execuções de código concorrendo pelo mesmo recurso. Podendo ser uma variável, constante, acesso a banco de dados, ou seja, qualquer recurso em que duas execuções querendo acessar um recurso durante o mesmo processo.

---
>Pode-se ter paralelismo sem concorência. Em casos que um processador tenha mais de um núcleo onde cada esteja executando trechos de códigos distintos e que não estão acessando um recurso em comum.

>Pode-se ocorrer concorência sem a existência de paralelelismo. Em casos que um processador que tenha apenas um núcleo e esteja alternando entre execuções que estão acessando uma mesma variável por exemplo.