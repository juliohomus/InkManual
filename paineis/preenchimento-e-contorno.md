# 🟡 Preenchimento e contorno

Este painel concentra todos as preferências para preenchimento e contorno.&#x20;

![](<../.gitbook/assets/image (50).png>)

Existem alguns elementos que são comuns para todos ou quase todos os modos. A _roda de cores_ apresenta as cores num arco do espectro de cores com um triângulo de saturação no centro. É possível usar a caixa ao lado para escolhe entre diferentes perfis de cores. Todos os modos de cor terão um canal _Alpha_ para transparência, o que é diferente da transparência para o objeto. O campo RGBA exibe e permite entrar com um código alfanumérico para a cor.  Logo abaixo, temos botões para gerenciamento de perfis de cores e um [seletor de cor](../ferramentas/conta-gotas.md). O _modo de mistura_ define como as cores do objeto serão misturadas aos objetos abaixo.&#x20;

![](<../.gitbook/assets/image (27).png>)

<details>

<summary>Modos de mistura</summary>

<mark style="color:red;">A desenvolver</mark>

</details>

Por fim, temos o _Desfoque_ que permite borrar as extremidades de um objeto. Este efeito é diferente daquele que obtemos com o [filtro desfoque](../filtros/desfoques/desfoque.md), que se aplica à toda imagem. E temos também a a transparência do objeto por inteiro.

![](<../.gitbook/assets/Peek 17-07-2022 00-16.gif>)

## Preenchimento & Contorno

{% hint style="info" %}
As abas de preenchimento e contorno têm exatamente os mesmos modos.
{% endhint %}

![](<../.gitbook/assets/image (5).png>)

No topo do painel ficam os modos de preenchimento e contorno. _Cor uniforme_ (sólida) __ irá aplicar uma cor homogênea, _gradiente linear_ produzirá um gradiente numa direção contínua, _gradiente radial_ dispõe o gradiente em círculos, _malha de gradiente_ permite criar gradientes mais complexos com múltiplos eixos e direções, por fim, temos o [preenchimento por padrão](../menu-objeto/padroes-de-preenchimento.md).

![](<../.gitbook/assets/image (4).png>)

### Gradiente linear e radial

O modo de gradiente sintetiza todas as funções da [ferramenta gradiente](../ferramentas/gradiente.md) em uma interface mais compacta e elegante. As preferências são exatamente as mesmas para o modo linear e radial.

![](<../.gitbook/assets/image (32) (1).png>)

Assumindo que você já tenha passado pela explicação da ferramenta gradiente, faremos aqui uma breve indicação dos mesmos elementos nessa nova interface:

1. Exibe a lista de gradientes disponíveis no arquivo
2. É um painel interativo do gradiente, onde se pode selecionar seus pontos para uma edição mais rápida. O campo para deslocamento por valor está logo abaixo.
3. Inverte o gradiente.
4. Muda o padrão de repetição.
5. Altera a cor do ponto selecionado e permite indicar um nível de transparência.
6. Outro campo para visualização dos pontos com ícones embaixo para adicionar e excluir pontos.

Temos, por fim, mais alguns botões entre os "modos" de preenchimento, mas que possuem funções diferentes. Primeiro temos os botões de _Amostra_ e _Indefinido_ ![](<../.gitbook/assets/image (29).png>). O botão de amostra irá criar uma amostra a partir do objeto selecionado, confira [um capítulo mais extenso](../paleta-de-cores.md#amostras-de-cores) sobre essa funcionalidade. O segundo botão permite definir o preenchimento ou contorno como _indefinido,_ ou seja, o objeto aparecerá em preto mas, na verdade, ele não tem cor. A utilidade prática disso é permitir, por exemplo, que [clones](../menu-editar/clonar.md) daquele objeto possam ter suas cores alteradas.

Os dois últimos botões ![](<../.gitbook/assets/image (46).png>) alteram a forma como caminhos sobrepostos se comportam quanto ao preenchimento, essa diferença fica clara na ilustração abaixo.

![](<../.gitbook/assets/image (26).png>)

## Estilo do contorno

As opções de contorno afetam as linhas entre em nós. Esta aba permite sua personalização avançada.

![](<../.gitbook/assets/image (38).png>)

Seguindo a ordem, temos a opção de modificar a largura do contorno e a unidade de medida; depois temos o tipo de traço, o campo seguinte basicamente permite mover o traçado internamente; os marcadores são desenhos que podem ser colocados no contorno, voltaremos neles mais adiante; a junção determina como os cantos ou junções entre linhas retas serão tratados, com 3 formatos diferentes e um modificador para o último; extremidades podem ser rentes, arredondadas ou prolongadas; por fim, temos a ordem interna entre preenchimento, marcadores e contorno. Todas essas opções estão ilustradas abaixo.

![](<../.gitbook/assets/image (53).png>)

Ao se clicar sobre os marcadores, temos um janela com os modelos disponíveis e algumas opções mais avançadas.

![](<../.gitbook/assets/image (47).png>)

LEMBRETE: falar sobre criação de marcadores.
