# 🔴 Lápis

A ferramenta lápis é uma daquelas que mais pode produzir resultados diferentes de acordo com os parâmetros utilizados. Sua função básica é criar traços, como de um lápis de verdade.

![](<../.gitbook/assets/image (8).png>)

As opções da barra de controle vão mudar completamente se ativada a sensibilidade para dispositivo de pressão. Vamos começar por ela, por ser relativamente mais simples. Note que se você não tiver um dispositivo de precisão, usando, por exemplo, apenas o mouse, o resultado será sempre uma linha uniforme.&#x20;

O campo "Min:" e "Máximo" se referem à largura mínima e máxima do traço. Cápsulas define o formato das pontas do traço. E suavização define o quanto o traço será simplificado, para reduzir as variações de precisão.

![](<../.gitbook/assets/image (18) (1).png>)

Sem ativar a sensibilidade à pressão, vamos ter outras opções na barra de controle. Primeiro é possível escolher o modo de desenho, entre caminho bézier regular, caminho espiral e b-spline \[confira a [Caneta bézier](caneta-bezier.md) para entender melhor sobre esses padrões de caminho]. Na prática, ao criar um traço, a aparência será praticamente idêntica num primeiro momento, você só perceberá a diferença ao usar o [editor de nós](editor-de-nos.md). Após criar o traço, é possível converter uma espiral ou b-spline em curvar regular com o botão ![](<../.gitbook/assets/image (24).png>).

{% hint style="info" %}
Usar uma suavização maior diminui o número de nós. Você também pode usar o menu **Caminho → Simplificar** (Atalho Ctrl + L) para diminuir o número de nós.
{% endhint %}

_Suavização_ repete a mesma função de suavizar a precisão do traço, mas com a ajuda adicional do botão seguinte ![](<../.gitbook/assets/image (33) (1).png>), você poderá modificar a suavidade interativamente. O botão à esquerda irá "fixar" o valor definido e você não poderá mais modificá-la.

![](<../.gitbook/assets/Peek 06-07-2022 03-31.gif>)

![](<../.gitbook/assets/image (9) (1) (1).png>)

Por fim, temos o campo Forma, onde você pode selecionar pinceis predefinidos ou usar um objeto criado para isso. As opções predefinidas são: _Nenhum,_ para um traço simples; _Entrada triangular_ e _Saída triangular,_ onde o pincel terá a forma de um triângulo nas direções indicadas; _Elipse,_ terá um formato circular; __&#x20;

_<mark style="color:red;">Da área de transferência; Curva da área de transferência;</mark> Último aplicado,_ irá usar o último formato utilizado.&#x20;

Após criar um traço, é possível usar o editor de nós para interagir com a alça que permitirá alterar a espessura do traço.

![](<../.gitbook/assets/Peek 07-07-2022 02-21.gif>)

Você pode pressionar **Shift** enquanto cria um traço para continuá-lo ou desenhar dentro do mesmo objeto.&#x20;

![](<../.gitbook/assets/Peek 07-07-2022 02-37.gif>)

<details>

<summary>Criar pontos</summary>

A ferramenta ainda tem uma função que permite criar pontos. Pressionar **\[Ctrl]** e click cria um ponto. **\[Shift] + \[Ctrl]** e click irá dobrar o tamanho do ponto. **\[Ctrl] + \[Alt]** e click irá criar um círculo pequeno de tamanho aleatório. **\[Ctrl] + \[Shift] + \[Alt]** e click irá criar círculos grandes de tamanhos aleatórios. Note que os os pontos são na verdade [círculos](circulo.md). Essa função pode ser útil, mas a ferramenta pulverizador permite criar resultados semelhantes mais complexos e mais rápido.

![](<../.gitbook/assets/Captura de tela de 2022-07-07 13-26-23.png>)

</details>

Uma última funcionalidade da ferramenta é o modo _rascunho,_ ativado ao manter **\[Alt]** pressionado enquanto se cria os traços. O objetivo deste recurso é emular a forma como artistas tentam criar traços mais precisos a partir de diversos traços. Isto funcionará melhor com traços contínuos do que com formas geométricas.

![](<../.gitbook/assets/Peek 07-07-2022 13-04.gif>)
