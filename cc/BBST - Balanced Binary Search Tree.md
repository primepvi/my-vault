Uma árvore BBST (Balanced Binary Search Tree) é uma extensão da árvore [[BST - Binary Search Tree]], portanto além das propriedades de busca proveniente de árvores BST, a BBST possui uma propriedade (invariância) de auto-balanceamento, ou seja, esse tipo de árvore se ajusta através de rotações, afim de manter a distribuição uniforme dos elementos na árvore, de forma que as operações performem em custo logaritmo (melhor caso). Portanto, em árvores BBST após qualquer operação a árvore deve se manter balanceada.

| Operações | Melhor Caso | Pior Caso |
| --------- | ----------- | --------- |
| Inserção  | O(log n)    | O(n)      |
| Remoção   | O(log n)    | O(n)      |
| Pesquisa  | O(log n)    | O(n)      |

