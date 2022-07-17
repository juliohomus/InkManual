# Traçar Bitmap

Traçar bitmap permite transformar imagens matriciais em vetores através de diversos parâmetros.

Para usar a ferramenta, selecione uma imagem matricial [importada](../../importar.md) e então vá em Caminho → Traçar Bitmap. Por padrão, a funcionalidade já está pré configurada para vetorizar traços típicos de desenho sobre papel, o tipo de trabalho mais comum para quem trabalha com ilustração. Basta clicar em _Aplicar_ para que a versão vetorial seja criada sobre a imagem original.

{% hint style="info" %}
A velocidade da vetorização dependerá do tamanho da imagem. Para reduzir o tamanho de uma imagem dentro do Inkscape use [Criar cópia bitmap](../../menu-editar/#criar-copia-bitmap). Mas lembre-se que ao reduzir uma imagem, você poderá estar perdendo informação e isso poderá reduzir a qualidade da vetorização.
{% endhint %}

!['Traçar bitmap' abre por padrão como um painel. Desacoplamos apenas para melhor visualização.](<../../.gitbook/assets/image (55).png>)

Na interface, nós temos abas para diferentes formas de vetorização. O primeiro, varredura única, irá produzir um único caminho para toda a figura. Multicolorido irá produzir vários caminhos para as diferentes varreduras usadas para gerar o desenho vetorial. Por fim, Pixel art serve para vetorizar imagens no estilo pixel art.&#x20;

Além disto, temos uma áre de pré-visualização, com as opções de habilitar atualização automática e um botão para atualização manual. Considerando o tamanho da imagem, você pode preferir desativar a atualização automática para reduzir a lentidão do processamento.

## Varredura única&#x20;

### Corte de brilho

#### Limiar

Definirá o limiar de brilho que será considerado na vetorização. Aumentar o limiar aumentará a sensibilidade da leitura da imagem, mas também irá trazer mais elementos indesejáveis, como pequenas manchas e marcas do papel para o vetor.

![](<../../.gitbook/assets/Peek 12-07-2022 12-17.gif>)

#### Inverter imagem

Irá inverter o brilho. Na exemplo abaixo, temos uma imagem com fundo preto com traço brancos. Para vetorizar apenas os traços, basta '_inverter imagem_'.

![](<../../.gitbook/assets/Peek 12-07-2022 13-02.gif>)

#### _Manchas_

Permite ignorar pequenas manchas, pontilhados na imagem. No exemplo abaixo, temos a mesma imagem (esquerda) vetorizada com o mesmo nível de brilho, o primeiro resultado usa o valor '2' como já vem predefinido. O segundo resultado usa o valor máximo, apenas para ilustrar como os pequenos pontos são ignorados e o traçado é mais homogêneo.&#x20;

![](<../../.gitbook/assets/image (59) (1).png>)

#### _Cantos suaves_

Trata da forma como os traços serão suavizados. O ajuste dessa preferência pode ser interessante em objetos com linhas retas, para evitar que a vetorização produza um resultado mais curvilíneo. No exemplo abaixo temos uma imagem matricial, seguida da conversão em vetor com _cantos suaves_ definido em 1,00 (valor padrão) e a seguinte tem esta preferência desabilitada.

![](<../../.gitbook/assets/image (54).png>)

#### _Otimizar_

É uma função basicamente tenta reduzir o número de nós. Isso é importante basicamente por uma questão de performance. Objetos com grande número de nós serão mais lentos para manipular. No exemplo abaixo, a vetorização do meio em que a otimização foi desativada tem cerca de 15.500 nós, enquanto a da esquerda, com a otimização no valor máximo, tem cerca de 12.000 nós. A diferença entre elas é quase imperceptível.&#x20;

![](<../../.gitbook/assets/image (56).png>)

Você também poderá usar o menu [Caminho → Simplificar](../#simplificar) para reduzir ainda mais o número de nós. No exemplo abaixo, temos uma redução de 15.500 nós para 2.300. Evidentemente a perda de detalhes é bem maior. Lembre ainda que você [Criar um cópia Bitmap](../../menu-editar/#criar-copia-bitmap) para reduzir o peso da imagem para o processamento.

![](<../../.gitbook/assets/image (43).png>)

#### Rastreamento assistido pelo usuário

Permite traçar apenas objetos dentro de uma imagem. Para isto, basta cobrir o objeto desejado com um caminho. A qualidade desta "separação" dependerá do contraste da imagem e do objeto sobreposto para criar o recorte. [Limiar](./#limiar) também pode ser ajustado para uma melhor definição da imagem. Essa função requer bastante processamento e poderá levar alguns segundos para processar imagens maiores.

![](<../../.gitbook/assets/image (46) (1).png>)

### Detecção de bordas

Detecção de bordas basicamente irá identificar áreas de contraste (bordas) na imagem. No exemplo abaixo, temos a primeira versão à direita da imagem original usando [corte de brilho](./#corte-de-brilho), logo em seguida temos a versão com _detecção de bordas_. &#x20;

![](<../../.gitbook/assets/image (37).png>)

Este modo tem apenas uma preferência, o _Limite de borda_, que considerará o nível de contraste entre os objetos. Quanto maior for, maior terá que ser o contraste entre os objetos para o traço. Todas as outras preferências as mesmas do modo anterior.

![](<../../.gitbook/assets/image (21).png>)

### Quantidade de cores

Este modo permite traçar a partir da mudança de cor, independente do brilho ou contraste. Possuindo apenas uma única preferência exclusiva para selecionar o número de _Cores_ usadas no cálculo do processamento da imagem. Note que, no exemplo abaixo, o valor padrão (que é 8) gerou uma imagem "invertida", onde os traços do pássaro eram o recorte do plano de fundo, isto se deve justamente pela forma como o cálculo do limiar entre cores é feito, ao subir o número de cores para 18, temos um resultado mais próximo da melhor traço dentro deste modo.

![](<../../.gitbook/assets/image (27) (1).png>)

### Traçar automaticamente



### Traçado de linha central&#x20;

Este modo permite permite criar linhas nos pontos centrais de contraste. Na prática, ele serve especialmente para vetorizar qualquer coisa que seja bem definida como uma linha.&#x20;

![](<../../.gitbook/assets/image (17).png>)





![](<../../.gitbook/assets/image (4) (1).png>)
