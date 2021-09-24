# Estrutura de dados

### Fila

São casos especiais de Listas, que possuem critérios específicos. Uma fila estabelece uma política FIFO (first in, first out), ou seja, primeiro que entra, primeiro que sai. Insere apenas no fim da fila, utiliza e remove apenas o primeiro elemento inserido.

### Pilha

O conceito de pilha está relacionado a empilhar valores. Uma estrutura de pilha, por outro lado, estabelece uma política LIFO (last in, first out), ou seja, último que entra, primeiro que sai. Uma estrutura de pilha oferece basicamente duas operações de manipulação, **PUSH**, para inserção no topo da pilha, e **POP**, para retirada do topo da pilha

### Lista

Listas são conjuntos de elementos, objetos, variáveis, tarefas, ou qualquer coisa que se possa enumerar e formar um conjunto. Uma lista ligada ou lista encadeada é uma estrutura de dados linear e dinâmica. Ela é composta por células que apontam para o próximo elemento da lista. Para "ter" uma lista ligada/encadeada, basta guardar seu primeiro elemento, e seu último elemento aponta para uma célula nula.

---

## Busca

### Busca Sequêncial

A partir de um determinado conjunto de valores, pode-se encontrar em qual posição está o valor que desejar. A busca sequencial não é a melhor forma quando há uma quande quantidade de dados. . A partir do primeiro item da lista, simplesmente passamos de item para item, seguindo o pedido sequencial subjacente até encontrar o que estamos procurando ou ficar sem itens. Se ficarmos sem itens, descobrimos que o item que procuramos não estava presente.

### Busca Binária

É uma busca mais eficiente, mas que exige um pré-requisito: que os valores estejam ordenados. Caso você possua uma lista com os valores ordenados de forma numérica ou alfabética, é possível fazer uma busca muito mais rápida. Ao invés de pesquisar a lista em sequência, uma busca binária começará examinando o item do meio. Se esse item for aquele que estamos procurando, a busca termina. Se não for o item correto, podemos usar a natureza ordenada da lista para eliminar a metade dos itens restantes. Se o item que procuramos for maior do que o item do meio, sabemos que toda a metade inferior da lista, bem como o item do meio, podem ser eliminados de uma consideração mais aprofundada. O item, se estiver na lista, deve estar na metade superior. Então, só é repetir esses passos até encontrar o valor desejado.

---

## Algoritmos de Ordenação

* Método de Ordenação Bolha (Bubble Sort):  Percorre várias vezes o vetor de maneira sequencial (passos). Em cada passo, compara cada elemento no vetor com o seu sucessor (p[i] com p[i+1]) e troca o conteúdo das posições em análise, caso não estejam na ordem desejada.  A ideia é percorrer o vector diversas vezes, e a cada passagem fazer flutuar para o topo o maior elemento da sequência.

* A estrutura chamada **Hash** é uma estrutura de dados especial, que associa chaves de pesquisa a valores. Seu objetivo é, a partir de uma chave simples, fazer uma busca rápida e obter o valor desejado.

* Estrutura em árvore : Dado um elemento central, todos elementos a esquersa são menores, e todos elementos a direita são maiores, e hierarquicamente eu posso ter o mesmo critério em diferentes níveis.
  







