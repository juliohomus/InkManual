# 🔴 Editor de nós

{% hint style="info" %}
Atalho: \[ F2 ]
{% endhint %}

Como um editor vetorial, a ferramenta de editor de nós é praticamente o coração do Inkscape. Mas para entendê-la, primeiro precisamos entender o próprio conceito de imagem vetorial.&#x20;

O desenho vetorial nada mais é do uma série de elementos que são calculados matematicamente. Se imaginarmos um retângulo criado em vetor, não importa quão grande ele seja, ele ocupará basicamente o mesmo espaço de armazenamento. Por outro lado, uma imagem rasterizadas (arquivos jpg, png, etc) são compostos de milhares de pontos únicos de cor (pixels) que juntos criam a impressão de uma imagem uniforme. Quanto maior for essa imagem, maior será o número de pixels e logo maior seu espaço de armazenamento.

O elemento básico do desenho vetorial é o nó. Podemos pensar num nó como um mero ponto sem qualquer conteúdo num espaço cartesiano. Esses pontos podem ser criados com algum vínculo, formando um caminho, definindo um preenchimento, etc. Lembre apenas que os nós em si mesmos são "invisíveis" e têm apenas a finalidade de receber as instruções matemáticas que formarão o objeto desejado.

Note, por último, que a ferramenta Editor de nós é focada precisamente na _edição_, ainda que tecnicamente seja possível adicionar novos nós a partir dela, você deverá usar outras ferramentas, como a [Caneta Bézier](caneta-bezier.md) para expandir um desenho.

O uso da ferramenta basicamente consiste em, após ativada, clicar sobre um ou mais objetos e, assim, revelar seus nós. Clicando então sobre os nós, você os estará selecionando e poderá modifilá-los.

![](<../.gitbook/assets/Peek 02-07-2022 22-22.gif>)

{% hint style="info" %}
Segurar **\[Ctrl]** enquanto se arrasta um nó fará com que ele se atraia para mover-se em linha reta.&#x20;
{% endhint %}

{% hint style="info" %}
Nós podem ser selecionados com a mesma interação da ferramenta [Seletor](seletor.md).
{% endhint %}

Indo para a barra de controle da ferramenta, pode
