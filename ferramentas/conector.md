# 🟡 Conector

{% hint style="info" %}
Atalho: \[ O ]
{% endhint %}

A ferramenta Conector é usada para criar conexões no estilo de diagrama entre objetos com o benefício de que essas conexões irão acompanhar os objetos se eles forem movidos. A ferramenta é bastante limitada e confusa do ponto de vista da UI/UX, e até mesmo a documentação sobre ela é escassa. Contudo, ela poderá atender as necessidades mais básicas de diagramação. \


Para contornar parte dos problemas de interface, vamos criar uma camada exclusiva para nossos conectores, isso facilitará o processo de personalização dos conectores posteriormente.&#x20;

![](https://lh5.googleusercontent.com/kh3OlUbChR4PCxjjhbxdMRn--UF9rdJGVf3RKEEePH8gm3rz-QkcCLL-j1HPr9ZFwmTw8GctCseR4cjUsxkFWBke89vSU9gWCuryXv4\_dALb8dQa4NtIXhL9oNQHCWsPAJRnSsKmbwfhYdvgKA)

\
Você pode criar conexões entre objetos e entre objetos e pontos de referência. Alguns objetos não podem ser selecionados, como texto, certifique-se que seus objetos estão convertidos em caminho, caso não consiga utilizar a ferramenta em algum deles. Para conectar objetos, clique sobre o retângulo branco centralizado em cada um deles que só aparecerá ao passar o mouse por cima. Qualquer ponto criado fora do centro do objeto (sinalizado pelo retângulo que aparecerá ao passar o mouse sobre ele) será apenas um ponto de referência. Você pode criar um ponto de referência para outro ponto de referência, mas isso não terá utilidade alguma (e é mais um dos problemas dessa ferramenta).

![](https://lh6.googleusercontent.com/p0EMX-k6wBAq1rWGTUbbkbmAOUMHH9WDPSsntub\_2DoeepiYV84hxbdYFJRz7NiiIV\_yUWm2uUy6IjpzYbhNdXKpC76yzXjGrjRMnp0xD71y2xwaHZK8llgW8PkTGKdFkU8XG\_QqpIwgUYacAg)

![](https://lh6.googleusercontent.com/Ru-ttZwEJCwa2AiXiWNV2SCBl6sCifh4zBaHEGjp0P0Un7UGDN-4smqVvP7KP8UWRCLOScQK5NJjtMUyZ2TSmWw27lZd2yKRtq-SSNbL2aCbetkco3wvWrcosh3ZuT2Yw9boFpT5o7xgb5mtvw)

A barra de controle tem basicamente três modificadores. Os dos primeiros botões alternam como objetos selecionados vão ser tratados pelos conectores. Primeiro você deve selecionar um objeto ou vários e depois clicar num desses botões, o primeiro irá impedir que os conectores perpassem os objetos, fazendo com que eles encontrem outros caminhos. O segundo irá permitir que os conectores sobreponham os objetos.&#x20;

O campo seguinte curvatura trata apenas de um arredondamento dos cantos dos conectores, apenas um artifício estético. Espaçamento se referência à distância que os conectores devem manter dos objetos, a unidade de medida provavelmente é o pixel. O botão seguinte tenta rearranjar os objetos para um melhor visual. Comprimento parece ter relação com o botão anterior, mas não consegui reproduzir seu efeito. O botão seguinte criaria conectores com setas apontando para baixo, mas também não consegui reproduzí-lo, assim como o último botão para não permitir sobreposição de formas.

Voltando para a sugestão de criar uma camada para os conectores, isso permitirá que você bloqueie outras camadas para editar seus conectores com maior facilidade. Outra dica útil é sempre criar a conexões na direção do ponto de origem para o destino. Isso também facilitará na personalização, por exemplo, ao colocar uma seta.

Preparamos um guia pratico para criação de diagramas [aqui](../tecnicas/criando-diagramas.md).
