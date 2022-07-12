# 🟡 Balde de tinta

A ferramenta Balde de tinta emula o efeito de preenchimento. A diferença aqui é que o preenchimento é na verdade um novo objeto.

![](<../.gitbook/assets/image (59) (1).png>)

O uso básico da ferramenta consiste em clicar sobre qualquer área do desenho que esteja de alguma forma confinada. A ferramenta não pode preencher áreas que não tenham confinamento.

![](<../.gitbook/assets/Peek 03-07-2022 14-13.gif>)



Olhando para a barra de controle, temos o primeiro campo que permite alterar a matriz de referência para o preenchimento.

![](<../.gitbook/assets/image (36).png>)

Em seguida, temos alguns modificadores. 1 Trata da faixa de variação da cor que será considerada como como padrão de preenchimento. Quanto menor o limiar, mais restrita será a faixa de cor sobre a que a ferramenta terá efeito.

![](<../.gitbook/assets/Peek 03-07-2022 14-29.gif>)

2 Expandir/encolhe permite que o preenchimento (que é um novo objeto) seja maior ou menor que a área afetada. Valores positivos expandem e valores negativos contraem. No exemplo abaixo usamos -5. Ao lado temos a sua unidade de medida.

![](<../.gitbook/assets/Peek 03-07-2022 14-33.gif>)

3 Permite fechar lacunas. Se a área de preenchimento tiver lacunas, elas poderão ser ignoradas com esse campo. Você poderá selecionar 3 níveis de precisão.

![](<../.gitbook/assets/Peek 03-07-2022 14-35.gif>)

{% hint style="info" %}
Essa ferramenta tem algumas limitações. Além de ser lenta, ela considera internamente zoom para calcular o preenchimento. O que na prática quer dizer que você precisará afastar o zoom para realizar o preenchimento com lacunas em alguns casos.
{% endhint %}
