# 🟡 Editor de nós

{% hint style="info" %}
Atalho: \[ F2 ]
{% endhint %}

Como um editor vetorial, a ferramenta de editor de nós é praticamente o coração do Inkscape. Mas para entendê-la melhor, primeiro você precisa entender o próprio conceito de imagem vetorial.&#x20;

<details>

<summary>Mais sobre desenho vetorial</summary>

O desenho vetorial nada mais é do uma série de elementos que são calculados matematicamente. Se imaginarmos um retângulo criado em vetor, não importa quão grande ele seja, ele ocupará basicamente o mesmo espaço de armazenamento. Por outro lado, uma imagem rasterizadas (arquivos jpg, png, etc) são compostos de milhares de pontos únicos de cor (pixels) que juntos criam a impressão de uma imagem uniforme. Quanto maior for essa imagem, maior será o número de pixels e logo maior seu espaço de armazenamento.

O elemento básico do desenho vetorial é o nó. Podemos pensar num nó como um mero ponto sem qualquer conteúdo num espaço cartesiano. Esses pontos podem ser criados com algum vínculo, formando um caminho, definindo um preenchimento, etc. Lembre apenas que os nós em si mesmos são "invisíveis" e têm apenas a finalidade de receber as instruções matemáticas que formarão o objeto desejado.

[Clique aqui](https://pt.wikipedia.org/wiki/Desenho\_vetorial) :earth\_americas: para mais informações sobre vetores.

</details>

Note, por último, que a ferramenta Editor de nós é focada precisamente na _edição_, ainda que tecnicamente seja possível adicionar novos nós a partir dela, você deverá usar outras ferramentas, como a [Caneta Bézier](caneta-bezier.md) para expandir um desenho.

O uso da ferramenta basicamente consiste em, após ativada, clicar sobre um ou mais objetos e, assim, revelar seus nós. Clicando então sobre os nós, você os estará selecionando e poderá modifilá-los.

![](<../.gitbook/assets/Peek 02-07-2022 22-22.gif>)

{% hint style="info" %}
Nós podem ser selecionados com muitas das mesmas interações da ferramenta [Seletor](seletor.md).
{% endhint %}

Indo para a barra de controle da ferramenta, temos os primeiros dos botões![](<../.gitbook/assets/image (38) (1).png>) que permitem criar novos nós entre os nós selecionados e excluir nós selecionados.

![](<../.gitbook/assets/Peek 02-07-2022 23-25.gif>)

O próximo botão ![](<../.gitbook/assets/image (33) (1) (1).png>)permite unificar dois nós, ainda que sejam de objetos diferentes.

![](<../.gitbook/assets/Peek 03-07-2022 00-04.gif>)![](<../.gitbook/assets/Peek 03-07-2022 00-06.gif>)

![](<../.gitbook/assets/image (29).png>) irá separar os nós selecionados de um caminho.

![](<../.gitbook/assets/Peek 03-07-2022 01-03.gif>)

![](<../.gitbook/assets/image (35).png>) permite unir os últimos nós de um caminho.&#x20;

![](<../.gitbook/assets/Peek 03-07-2022 01-07.gif>)![](<../.gitbook/assets/Peek 03-07-2022 01-18.gif>)

![](<../.gitbook/assets/image (40) (1).png>) irá fazer o exato oposto, excluindo a união entre os caminhos selecionados.

![](<../.gitbook/assets/Peek 03-07-2022 01-21.gif>)![](<../.gitbook/assets/Peek 03-07-2022 01-23.gif>)

Os próximos botões ![](<../.gitbook/assets/image (36) (1).png>) mudam como as alças dos nós vão se comportar. Na ordem, o primeiro torna o nós partindo do nó selecionado reto. Se o nó interconectado também estiver definido com esse padrão, não haverá alça de modificação. O segundo torna a alça "suave", criando uma continuidade entre os caminhos dois lados do nó. O terceiro torna os caminhos de ambos os lados simétricos. O último é útil para redefinir a suavidade de um nó rapidamente.

{% hint style="info" %}
Note que ao criar nós com a [Caneta Bézier](caneta-bezier.md) apenas criando pontos interconectados, eles serão do primeiro padrão, sem alças de curvatura. Já ao criar pontos se ajustando as curvaturas, eles serão no padrão suave.
{% endhint %}

![](<../.gitbook/assets/Peek 03-07-2022 01-29.gif>)

Os botões seguites ![](<../.gitbook/assets/image (17).png>) permitem converter o segmento entre dois nós em uma linha reta ou em uma curva. A primeira vista, eles podem parecer uma redundância dos botões anteriores. Mas a diferença é que ao eles permitem realizar suas operações sem afetar o caminho anterior.

![](<../.gitbook/assets/Peek 03-07-2022 10-34.gif>)![](<../.gitbook/assets/Peek 03-07-2022 10-36 (1).gif>)



Os botões ![](<../.gitbook/assets/image (2) (1).png>) permitem converter uma forma (círculos, retângulos, etc.) em caminhos simples, e converter contornos em caminhos. Logo em seguida, é possível ver um campo de posicionamento manual do nó e sua unidade de medida: ![](<../.gitbook/assets/image (21) (1).png>)

![](<../.gitbook/assets/Peek 03-07-2022 01-50.gif>)![](<../.gitbook/assets/Peek 03-07-2022 01-51.gif>)

Os botões seguintes, ![](<../.gitbook/assets/image (16) (1).png>) permitem ajustar a visibilidade dos contornos dos objetos usados como recorte e máscara.&#x20;

![](<../.gitbook/assets/Peek 03-07-2022 01-58.gif>)![](<../.gitbook/assets/Peek 03-07-2022 02-03.gif>)

O botão ![](<../.gitbook/assets/image (32).png>) irá mostrar o parâmetro editável de um [efeito de caminho](../efeitos-de-caminho-lpes/) ativo. No caso abaixo, tínhamos o efeito de caminho Curva, onde podemos editá-lo sem precisar abrir o painel de Efeitos de Caminho. O botão ![](<../.gitbook/assets/image (48).png>) permite ver o contorno do objeto original sem o efeito de caminho.

![](<../.gitbook/assets/Peek 03-07-2022 02-08.gif>)![](<../.gitbook/assets/Peek 03-07-2022 02-12.gif>)

Por fim, vimos temos os botões ![](<../.gitbook/assets/image (39) (1).png>) que permitem exibir alças de transformação e rotação e as alças de Bézier respectivamente.&#x20;

![](<../.gitbook/assets/Peek 03-07-2022 02-16.gif>)![](<../.gitbook/assets/Peek 09-07-2022 13-26.gif>)



### Atalhos:

|                              |                                                 |
| ---------------------------- | ----------------------------------------------- |
| Shift + Ctrl + C :arrow\_up: | Transforma forma em caminho                     |
| Ctrl + Alt + C :arrow\_up:   | Transforma contorno em caminho                  |
| 7                            | Mostrar parâmetro editável de efeito de caminho |
