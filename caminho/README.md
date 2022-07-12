# Caminho

Operações entre objetos são feitas principalmente pelo menu Caminho. Aqui estão diversas opções comuns&#x20;

![](<../.gitbook/assets/image (51).png>)



Note, antes de mais nada, que caminhos possuem uma "área" interna, a não ser que sejam apenas dois nós interligados por uma linha reta. Qualquer outra forma irá possuir uma área interna, ainda que os nós não estejam traçados entre si. Os objetos também não precisam estar com preenchimento ou contorno para realizar as operações de caminho.

![](<../.gitbook/assets/Peek 11-07-2022 01-41.gif>)

#### Converter em caminho

Permite transformar um objeto especial em caminho. No exemplo abaixo, por exemplo, temos um texto convertido em caminho. Essa operação tem várias utilidades diretas e indiretas, dentro e fora do programa.

![](<../.gitbook/assets/image (42).png>)

#### Converter contorno em caminho

Permite converter um contorno em caminho. Se o objeto já tiver um preenchimento, contorno e preenchimento serão criados como objetos diferentes.

![](<../.gitbook/assets/image (38).png>)

#### União&#x20;

![](<../.gitbook/assets/image (30).png>)

A operação de união permite unir os caminhos de vários objetos em um único objeto. Caminhos sobrepostos serão "unidos" dentro do mesmo caminho.

#### Diferença

Diferença irá subtrair caminhos sobrepostos. No caso da seleção de múltiplos objetos, a diferença será feita na ordem em que os objetos foram selecionados sucessivamente (usando Shift + click para adicionar objetos à seleção). No exemplo abaixo, temos círculos que foram selecionados na ordem indicada para gerar o resultado do meio, na construção da direita, temos a operação feita manualmente em cada etapa.

![](<../.gitbook/assets/Peek 11-07-2022 01-22.gif>)

#### Intersecção

Irá encontrar a intersecção entre os objetos selecionados. Neste caso, não importa a ordem de seleção porque a intersecção é sempre a parte comum entre todos os objetos selecionados.

![](<../.gitbook/assets/image (20).png>)

#### Exclusão

A exclusão irá remover a área comum entre dois objetos. Essa operação não pode ser feita entre múltiplos objetos, logo, ao se selecionar vários objetos, o resultado não será a exclusão da área comum de todos objetos, mas sim de cada operação sucessiva.

![](<../.gitbook/assets/image (43).png>)

#### Divisão

Permite recortar um objeto pelo que está sobreposto a ele. Só funciona com dois objetos. Se forem selecionados vários objetos, apenas os dois últimos na ordem de sobreposição serão usados na operação. No exemplo abaixo, a parte recortada foi afastada para efeito ilustrativo.

![](<../.gitbook/assets/image (12).png>)

#### Cortar caminho

irá realizar um processo parecido com a divisão, a diferença aqui é que o recorte, além de ser uma linha reta entre os pontos de intersecção dos dois objetos, irá remover o caminho entre os nós. Note que ao usar essa operação, ela irá remover o preenchimento, se o objeto não tiver um contorno, ele parecerá invisível. Essa função também só pode ser usada com dois objetos.

![](<../.gitbook/assets/image (23).png>)

#### Combinar

Combinar irá realizar a mesma função que [união](./#uniao), mas preservará os caminhos. Pode ser aplicada a múltiplos objetos.

![](<../.gitbook/assets/image (54).png>)

#### Separar

Essa função permite separar caminhos em objetos distintos que foram combinados com a função anterior. Pode ser aplicada a múltiplos objetos.

![](<../.gitbook/assets/image (21).png>)

#### Dividir caminho

Esta funcionalidade permite separar caminhos de uma forma mais inteligente, mantendo caminhos que estão relacionados juntos. O exemplo mais comum dessa funcionalidade é ao separar letras de um texto convertido em caminho. Devido à forma como as fontes são feitas, a função convencional para _separar_ produz outros objetos, especialmente dentro dos espaços das letras, dividir caminho resolve esse problema.

![](<../.gitbook/assets/image (57).png>)

#### Comprimir e expandir&#x20;

Permite comprimir ou expandir um caminho manualmente.

#### Expansão/Compressão dinâmica

![](<../.gitbook/assets/Peek 11-07-2022 02-32.gif>)

#### Expansão/Compressão vinculada

Cria uma espécie de clone do objeto com o qual se manterá um vínculo no seu formato, permitindo realizar expansão ou compreesão dinâmica independentemente.

![](<../.gitbook/assets/Peek 11-07-2022 02-33.gif>)

#### Preencher entre caminhos

É, na verdade, um [efeito de caminho](efeitos-de-caminho-lpes/). Ele irá preencher o espaço vazio entre dois caminhos com um novo objeto. Após realizar a operação, você pode [converter em caminho](./#undefined) para desvincular os objetos. A parte que será preenchida será aquela entre nós sem caminho.

![](<../.gitbook/assets/image (34).png>)

#### Simplificar

Irá diminuir o número de nós de um objeto, diminuindo sua complexidade.

![](<../.gitbook/assets/Peek 11-07-2022 02-50.gif>)

#### Inverter

Permite inverter a ordem dos caminhos, útil para mudar a direção de marcadores.&#x20;

![](<../.gitbook/assets/image (33).png>)

