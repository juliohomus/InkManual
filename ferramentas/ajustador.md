# 🟡 Ajustador

{% hint style="info" %}
Atalho: \[ W ]
{% endhint %}

{% hint style="warning" %}
Como o inkscape ainda não tem aceleração por GPU, entre outras limitações técnicas, o uso desta ferramenta poderá ser limitado.
{% endhint %}

A ferramenta ajustador permite aplicar interativamente várias formas de distorções para os objetos. Note que a ferramenta apenas modifica os objetos previamente selecionados.

![](<../.gitbook/assets/image (14) (1).png>)![](<../.gitbook/assets/image (53) (1).png>)

Os primeiros modificadores da barra de controle dessa ferramenta permite modificar a _largura_ do ponteiro do mouse e a _força_ da ação, ou seja, é um multiplicador do efeito que iremos selecionar logo mais. Para simplificar, vamos logo tratar do último modificador, _fidelidade_ corresponde ao nível de detalhe das deformações. Quanto maior a fidelidade, maior o número de nós e consequentemente mais pesado ficará o processamento do seu arquivo.

![](<../.gitbook/assets/image (57) (1).png>)

Chegamos então aos modos de ajuste. Alguns deles são específicos para um grupo de vários objetos, geralmente pequenos, outros atuam melhor sobre objetos (bem) maiores. Para exemplificá-lo criamos um ladrilho de 30x30 objetos (cada com cerca de 10x10px). tenha isso em mente ao replicar esses efeitos em outros trabalhos.

O primeiro modo ![](<../.gitbook/assets/image (37) (1) (1) (1).png>) move objetos em qualquer direção.

![](<../.gitbook/assets/Peek 23-06-2022 04-24.gif>)

O modo ![](<../.gitbook/assets/image (1).png>) irá atrair os objetos na direção do cursor.

![](<../.gitbook/assets/Peek 23-06-2022 04-26.gif>)

O modo ![](<../.gitbook/assets/image (58) (1) (1).png>) move os objetos em direções aleatórias.

![](<../.gitbook/assets/Peek 23-06-2022 04-29.gif>)

O modo ![](<../.gitbook/assets/image (15).png>) permite reduzir ou aumentar (pressionando Shift) os objetos.&#x20;

![](<../.gitbook/assets/Peek 23-06-2022 04-30.gif>)

O modo ![](<../.gitbook/assets/image (10) (1) (1).png>) permite rotacionar os objetos. Pressione Shift para rotacionar em sentindo anti-horário.

![](<../.gitbook/assets/Peek 23-06-2022 04-34.gif>)

O modo ![](<../.gitbook/assets/image (31).png>) permite duplicar objetos e excluí-los, apertando shift. A cópia é feita em cima do próprio objeto original.Para ilustrar, vamos ver apenas a exclusão:

![](<../.gitbook/assets/Peek 23-06-2022 04-38.gif>)

Vamos pular alguns modos para continuarmos com o exemplo do ladrilho:

O modo ![](<../.gitbook/assets/image (35) (1) (1).png>) permite pintar os objetos de uma cor selecionada.

{% hint style="info" %}
Lembre de desvincular seus clones, se estiver usando.&#x20;
{% endhint %}

![](<../.gitbook/assets/Peek 23-06-2022 04-42.gif>)

O modo ![](<../.gitbook/assets/image (56) (1).png>) vibra as cores já existentes nos objetos.

![](<../.gitbook/assets/Peek 23-06-2022 04-49.gif>)

O modo ![](<../.gitbook/assets/image (40) (1) (1).png>) desfoca os objetos.

![](<../.gitbook/assets/Peek 23-06-2022 04-50.gif>)

Os próximos modos funcionam melhor em objetos grandes ou com um grande número de nós. Ainda que um objeto seja grande, mas tenha apenas 4 nós (como um retângulo), isso não será suficiente para que a ferramenta funcione perfeitamente. No exemplo a seguir usamos um retângulo em que adicionar vários nós intermediários.

O modo ![](<../.gitbook/assets/image (33) (1) (1) (1).png>) permite empurrar as bordas dos objetos:

![](<../.gitbook/assets/Peek 23-06-2022 04-56.gif>)

O modo ![](<../.gitbook/assets/image (2) (1) (1).png>) permite encolher as bordas do objeto na direção do cursor.

![](<../.gitbook/assets/Peek 23-06-2022 04-57.gif>)

O modo ![](<../.gitbook/assets/image (3) (1).png>) torna as bordas de um objeto ásperas.

![](<../.gitbook/assets/Peek 23-06-2022 04-59.gif>)
