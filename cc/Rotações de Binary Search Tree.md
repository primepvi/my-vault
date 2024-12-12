A operação de rotação em árvores binárias de busca é efetuada afim de balancear á árvore. Essa rotação é efetuada em sub-árvores com dois de altura (três níveis). Existem diversas formas de rotação, cada uma possui um contexto onde deve ser aplicada, o contexto vai variar de acordo com a composição da sub-árvore a ser rotacionada.
##### right rotation
Na rotação para direita considerando y como filho a esquerda do nó cabeça (x), temos que alterar o filho a direita de x para o filho a esquerda de y, depois realocamos x para a esquerda de y, logo agora y será o novo nó cabeça.

y = x.right
x.right = y.left
y.left = x
return y
##### left rotation
Na rotação para esquerda considerando y como filho a direita do nó cabeça (x), temos que alterar o filho a esquerda de x para o filho a direita de y, depois realocamos x para a direita de y, logo agora y será o novo nó cabeça.

y = x.left
x.left = y.right
y.right = x
return y

![[SmartSelect_20241212_182944_Obsidian.jpg]]

