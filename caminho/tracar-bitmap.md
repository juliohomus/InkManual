# Traçar Bitmap

Traçar bitmap permite transformar imagens matriciais em vetores através de diversos parâmetros.

Para usar a ferramenta, selecione uma imagem matricial [importada](../importar.md) e então vá em Caminho → Traçar Bitmap. Por padrão, a funcionalidade já está pré configurada para vetorizar traços típicos de desenho sobre papel, o tipo de trabalho mais comum para quem trabalha com ilustração. Basta clicar em _Aplicar_ para que a versão vetorial seja criada sobre a imagem original.

{% hint style="info" %}
A velocidade da vetorização dependerá do tamanho da imagem. Para reduzir o tamanho de uma imagem, use [Criar cópia bitmap](../menu-editar.md#criar-copia-bitmap). Mas lembre-se que ao reduzir uma imagem, você poderá estar perdendo informação e isso poderá reduzir a qualidade da vetorização.
{% endhint %}

!['Traçar bitmap' abre por padrão como um painel. Desacoplamos apenas para melhor visualização.](<../.gitbook/assets/image (55).png>)

Na interface, nós temos abas para diferentes formas de vetorização. O primeiro, varredura única, irá produzir um único caminho para toda a figura. Multicolorido irá produzir vários caminhos para as diferentes varreduras usadas para gerar o desenho vetorial. Por fim, <mark style="color:red;">pixel art</mark>.

O primeiro ajuste, L_imiar_, irá definir o limiar de brilho que será considerado na vetorização.&#x20;

![](<../.gitbook/assets/Peek 12-07-2022 12-17.gif>)

Inverter imagem irá inverter o brilho. Na exemplo abaixo, temos uma imagem com fundo preto com traço brancos. Para vetorizar apenas os traços, basta '_inverter imagem_'.

![](<../.gitbook/assets/Peek 12-07-2022 13-02.gif>)

_Manchas_ permite ignorar pequenas manchas, pontilhados na imagem. No exemplo abaixo, temos a mesma imagem (esquerda) vetorizada com o mesmo nível de brilho, o primeiro resultado usa o valor '2' como já vem predefinido. O segundo resultado usa o valor máximo, apenas para ilustrar como os pequenos pontos são ignorados e o traçado é mais homogêneo.&#x20;

![](<../.gitbook/assets/image (59).png>)

_Canto suaves_ trata da forma como os traços serão suavizados. Reduzir totalmente&#x20;
