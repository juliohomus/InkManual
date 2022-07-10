# 🟡 Camadas e Objetos

A partir do Inkscape 1.2 o painel de camada foi reformulado e agregou o painel de objetos.&#x20;

![](<../.gitbook/assets/image (45) (1).png>)

Esse painel permite ver todos os elementos do seu arquivo de forma condensada e organizada. Vamos para uma breve descrição dos botões do topo do painel.

![](<../.gitbook/assets/image (5) (1) (1).png>)

O primeiro botão ![](<../.gitbook/assets/image (42) (1).png>) permite mudar a visualização do painel só para camadas ou para todos os elementos. O botão _adicionar camada_ ![](<../.gitbook/assets/image (7) (1).png>) faz literalmente isso, com o auxílio da janela a seguir:

![](<../.gitbook/assets/Captura de tela de 2022-06-22 18-41-43.png>)

No primeiro campo você poderá inserir um nome arbitrário para a camada. _Disposição_ define a posição da camada na árvore de camadas, Acima da atual, Abaixo da atual e subcamada da atual onde a camada será criada dentro da camada atualmente selecionada.

Os últimos botões permitem ![](<../.gitbook/assets/image (12).png>) mover camada selecionada apra cima, ![](<../.gitbook/assets/image (30).png>) mover camada selecionada para baixo e ![](<../.gitbook/assets/image (47) (1).png>) excluir a camada selecionada.

Na árvore do painel são exibidos todos os elementos do arquido dentro da sua hierarquia. Note que apesar do ícone da camada indicar uma "página", as páginas criadas com a ferramenta [Páginas](../ferramentas/paginas.md) não aparecem dentro desse painel e não possuem posição na hierarquia. Objetos não são vinculados à páginas.&#x20;

![Exemplo de alguns elementos dentro da hierarquia](<../.gitbook/assets/image (22).png>)

{% hint style="info" %}
Objectos só podem ser agrupados sob a mesma camada. Se eles estiverem espalhados entre diversas camadas, eles serão agregados na camada do primeiro objeto selecionado.
{% endhint %}

Ao passar o mouse sobre os elementos da árvore do painel, aparecerão três ícones: o primeiro, com formato de um olho, permite exibir ou ocultar aquele elemento, o ícone de cadeado permite bloquear o elemento, o que faz com que ele não possa ser selecionado. Por fim, a cor de destaque indica a cor da camada e permite modificá-la.

![](<../.gitbook/assets/image (38) (1).png>)

### Visibilidade e Bloqueado

Visível e bloqueado são funções básicas da experiência de trabalho com o Inkscape. Eles podem ser desativados e ativados para objetos e grupos individuais e para camadas inteiras. Por padrão, todos objetos são criados como visíveis e desbloqueados. Ao tornar um objeto invisível, ele não pode ser selecionado além de não aparecer tanto do ponto de visto do usuário quanto das próprias operações do programa, como alinhamento, por exemplo, de certa forma é como se o objeto não existisse. Enquanto que bloquear um objeto apenas faz com que ele não seja selecionável. Isso é particularmente útil, por exemplo, nos casos em que você não quer que um objeto interfira na seleção de outros objetos em que ele está sobreposto.

![](<../.gitbook/assets/Peek 01-07-2022 13-04.gif>)

Também é possível acessar o menu de contexto para cada elemento da árvore. O menu de contexto para objetos e grupos é exatamente o mesmo disponível ao se clicar com o botão direito do mouse sobre no canvas, por isso vamos apenas mostrar aqui o menu de contexto para camada, já que ele aparece exclusivamente aqui.&#x20;

![](<../.gitbook/assets/image (25) (1).png>)

Todas as entradas do menu são autoexplicativas, mas vale mencionar a opção Camada para Grupo que permite converter uma camada em grupo. Objetos dentro da hierarquia de uma camada não estão "relacionados" para quase todos os fins práticos de edição. Você pode movê-los e editá-los sem que isso cause efeito sobre os demais objetos.&#x20;

{% hint style="info" %}
Existe na [barra de status](../barra-de-status.md) um indicador da camada atual.

![](<../.gitbook/assets/image (20).png>)
{% endhint %}

### Menu  Camada

![](<../.gitbook/assets/image (2).png>)

O menu para Camada é bastante autoexplicativo, tendo só mais funções debtro daquilo que já abordamos.&#x20;

### Atalhos

| Atalho           | Função                             |
| ---------------- | ---------------------------------- |
| Shift + Ctrl + L | Abre o painel de Camadas e Objetos |
|                  |                                    |
|                  |                                    |
