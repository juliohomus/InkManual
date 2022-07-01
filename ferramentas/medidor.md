# Medidor

{% hint style="info" %}
Atalho: \[ M ]
{% endhint %}

Essa é uma daquelas ferramentas muito mais avançadas do que pode parecer. Sua função é mensurar distâncias e ângulos, mas há vários modificadores úteis que você deve entender para realizar trabalhos mais complexos. Note, antes de mais nada, que a ferramenta não cria um objeto, as informações na tela são apenas temporárias mas podem ser convertidas em vetor, como veremos adiante.

É bem possível que para ilustradores e artistas convencionais, essa ferramenta não tenha muita utilidade, mas para quem trabalha com desenhos técnicos e com precisão de ângulos e medidas (ex: webdesign, isométricos, CAD, etc.), ela é totalmente necessária.

![](https://lh6.googleusercontent.com/GDeJ89nzB6eV8YVMK44Ui0AnQII2bhhYgrd4hcC\_GBq6n\_o5j3BlDJdMIA5Vea-Zscup94WXCU7Pl-Kdq4okcluAg-3E5faQKcI-K2lWpWmu7e-KdP53Bvy0cuPLXvtTXaK-pyCdvqHdIn69tQ)![](https://lh4.googleusercontent.com/ONyaKXNnq4m3SM9ifVNMV93kPFiqM1YXZZQG\_pnN9L5ypToBjgSI9p3bieD-83ppHPTzvh4tEEZIuhn8\_u6WliGz9hVgcZ\_Nn74GWUia8q1ZR0H-fW967vzTKvHek3sZtWkgBRvIjZKJq\_ZOjA)

O primeiro uso da ferramenta é simplesmente levando-a aos objetos, o que revelará suas medidas. No caso, temos aqui um retângulo com 313,77px de largura, 281,73px de altura. Os X e Y seguintes se referem à posição (seu canto esquerdo e sua base, respectivamente) em relação ao canvas/página (que tem seu eixo X no canto esquerdo mas seu eixo Y no topo). Para ficar claro, compare a figura da esquerda e da direita. No caso da direita, deslocamos o objeto 20px para cima e 20px para a esquerda, o que na ferramenta será exibido como uma distância negativa de -20px para ambos os lados. Por fim, o que o programa chama de comprimento é o cálculo das suas dimensões, seria equivalente ao perímetro, para a maioria dos casos.

\


![](https://lh4.googleusercontent.com/zHIOmvR3bK0D1pTSYt0KOsnnfmgnWjhGLozPVm2knaoUUYyC5o5UPvCXcCbnOSizTcX70xc3urXJSph2SxEJUsbERExuYPCbc7EVHjMZiDTdOcrTLh0HBMECLlK-lxGqio0Bjxq9i4GLM-RYkQ)

Indo para a sua barra de controle, o primeiro campo se refere apenas ao tamanho da fonte que será usada para exibir as medidas ou gerá-las como uma anotação (veremos a seguir). Em seguida, precisão se refere ao número de casas decimais após a vírgula. A escala é um redimensionamento das medidas para fins de referência. Se o objeto que você está medindo é uma reprodução em 1:2 do seu tamanho real, você provavelmente vai querer mudar a [escala](https://cursoenemgratuito.com.br/escala/) para 50%. E unidades define a unidade de medida da mensuração.&#x20;

![](https://lh5.googleusercontent.com/yANj5hibJAJAxOdGuLCdjdguYKr2NL3C1A6dFVgv2d1nFTDJC4iKvSFe09gm2EpvYPZLGHdRCc0BA8BOdpElJI54GZxum1FBdDVg7XT\_2pRsCFThWaPhnBQFi3nDzQaHip-oXJRYf4BoPdYbiw)

Para finalmente criar medidas, basta clicar e arrastar o cursor, as informações serão geradas automaticamente de acordo com os modificadores. Como é possível ver no gif acima. O medidor irá por padrão mostrar todas as distâncias entre todos os objetos perpassados. Note que a interface do medidor apresenta uma linha azul seguida de um número em retângulo azul, essa é a distância ou “régua” que você está criando. A linha vermelha é perpendicular a esta distância e forma então um arco vermelho cujo ângulo fica representando no retângulo verde. No retângulo cinza claro é possível ver a medida da linha perpendicular e nos retângulos esculos estão as distâncias dos pontos de intersecção. Note que cada ponto é demarcado por um “x” no seu início e fim.

\


![](https://lh3.googleusercontent.com/ltlKhgbJFBFMjnniovVXxufdB4P\_HLAqzRFdIzMBrd1RSRdi1nJreW5wT6naRDHiD0fkNQdpo-Qg8LLBcXT3RwgadpuXX4aEP7hcPWJl2peUTw02ApExm2hTgnPBo4OT2-nPAOToQf57HvDIjQ)

O primeiro modificador a seguir permite criar medidas apenas dos objetos selecionados. Se você não selecionar qualquer objeto antes de usar a ferramenta, não haverá diferença. O próximo botão irá alternar entre a exibição das medidas fora da área dos objetos perpassados. Se sua medida não passar por qualquer objeto, ela não fará diferença. Note no gif abaixo que a ferramenta está ativada e ao desativá-la a medida da distância do espaço perpassado pela ferramenta é, então, exibido.

![](https://lh3.googleusercontent.com/OYIgegOB5fBQLdM-K24CI8SxPHbe\_SWCNKGRmDy34AMMBfJB9nVp5IuNhskqJfZH2Owj9G5GlO-4r67G9Jv1YqQuHTA9X0iFAtXDOqDwXfbPKHDilRiRLZMxKE6qhRfscCOcqSF87ZyROkcXmg)

O modificador seguinte ![](https://lh5.googleusercontent.com/vzjmD7BcYwrlJ\_vFJpPoaO1sHiRr2uX6rXyrJm3YLTpkLzfqFmD9gNSzXuAT-BXESIUN9tFYnnLiYoafISKKL5Jp7b8we-MyLj0RNjCGvqCQtf7mxRkLkq20oNZNvRvqvy2DmRz8FVyAD-kUjw) irá mostrar todas as medidas dos objetos perpassados assim como a distância entre eles. Se desativada, só será exibida a medida do deslocamento criado.&#x20;

![](https://lh6.googleusercontent.com/qT23p3Uf1rF\_HOb3AWjQyzr-ytcNSLYepNltN698Mh8YwofqwCwTTe7yT-AkFMr2pKmlycjX-F5EiGR7ZXqaMuR0rv-jHVzEQYmSziQWGc0B7STVsp9KXugkag-Au4YsqG033TqmAmn34UbmUw)

O penúltimo botão ![](https://lh4.googleusercontent.com/5sKDaZOJo1jVQErtyq-4queinLisWuZEhdeeWUp0mZLwdav9B23uklotderQz7fy-qdZhgFLm46C7Ze9djiYjDif\_NY-CLtgguivyPNgrbyYs1-hEOAfOo5k\_X40GiNYPy93w0yd7EVwBRxmvA) permite exibir medidas entre objetos escondidos por sobreposição. No gif abaixo temos dois quadrados sobrepostos, o da esquerda está transparente para facilitar a compreensão. Quando ativado, o modificador muda a forma como a ferramenta mede os objetos, mostrando a medida da sobreposição.&#x20;

E o último ![](https://lh3.googleusercontent.com/SyRbWkeayO9Mdj6QHBk2nQELXYju1nVj0XWeNSE\_dukr8IFBNIhFRrLfZgiqYHneziHSDtWS6vXfJIpjESJzX9QcZnbp1YEJc18hiz8BhmOHX9OvxeA9eHbr5mXc476SnZzDL6HpPITSblw3qQ) alterna entre mensurar objetos de todas as camadas ou apenas da camada atual.

\


![](https://lh3.googleusercontent.com/MaK8B1eP8uAhoBLatvyBCeoEqMm-chphEoOFTdV4kuopdNOsBdnnxHPCGEHK5XX6gIXVl9Bm431uGWSxZm3DWr5o8w7-i4FDah\_1hU4pXuragcOwGile6fDW7JlsVl3UCWJCO0k80jlQ-9uasQ)

\


A seguir temos algumas opções de manipulação da ferramenta. A primeira inverte o arco/ângulo da medida. O novo arco sempre erá uma subtração de 180º menos o ângulo atual, no caso da imagem abaixo, 180 - 45 = 135. Esse é o novo arco/ângulo apresentado.

\


![](https://lh6.googleusercontent.com/OlBWQmcVBoR7SoDSj2XnWWxavnk0x0mf8DD-OeVFRLA1GDyxwMvppHMJZTyQX0FmfuEPiE\_MavB\_ZXnv1VIjOJRvhA-3WzyGtm3OTk4rGFqo8Vh3GJjad648oBuauHb\_Ba0qqflIAGEBJmZeNg)

A segunda cria uma “cópia fantasma” da medida atual que ficará em tela enquanto você poderá criar uma outra medida. Note que nem a medida real nem a medida “fantasma” estão escritas no seu documento e são apenas ferramentas temporárias.

\


![](https://lh4.googleusercontent.com/lXBb3z-z7x2MjEqDCk5Be6k18znPhTdQ8YQEYlT\_\_1mENhoHXXhiVrPxI4aePXh9rXbFIfC2dkursR0-0nJHqNOpN3Ht0k0gZxZc-aT1\_C8Q3aJ0r9XLz0xnNazpcxGmDKGo6hjTdA5zjgHqxA)

A seguinte ![](https://lh4.googleusercontent.com/qnkfCXlO52Wa5ifXaCo2FQJqyij3zvxXNm3hS903UJKA4-APWQaXEE-Y6Thby9jxYbxJpqMGxhSCpEIjDos3p2oc4DyeeAG-659jbkaMNvict7g\_lE1OxOWjwpMp0dfdig3laXexzzqYOuwQVQ) permite simplesmente transformar sua medida em guias. Você pode manualmente modificar as guias depois de criadas.

\


![](https://lh3.googleusercontent.com/cyd75mnaN0EZGDsThXNvh6C2NTF-70GmNY\_wD9vm9-dVNJFTK2vLY0VI2zGNDv4kpbrXjIK3ZlkkGioP1yqweWVzyb0J\_3DY3vcaYuzqOrsDpS2LOGhKo3Ua6TqJ4IJLHvpPBentAyP2bM-1Kw)

\


A próxima ![](https://lh4.googleusercontent.com/Q3EUZKhI6GstFFMq8Onuq8IXxkwNWK8vpAh8SuLXNmhuLthl3xvV\_\_moSKapoizCYCOxhyAimZ21XI20MYP6ZlIXefupSIoll-jNQuCNO4ZY\_ZQKI6xFI674kMGqIeWU3yJGzSF11Eom2XA5DQ) cria um desenho editável a partir da medida criada em tela. A última ![](https://lh5.googleusercontent.com/dSMLQttZcecyFOEu2aPU4zrCp3ea2Pl6dndYfsJq7rB7ZEuDcr-tkiNqW\_z6NN3YdM8SOBYEvWsrEX9SzVU8ZvYnumdTIJbs84N-EVW3AgX-MGYUkXVA4DwaBv8Sd8yon1C8ISmIBmmYBnBlyg) cria um desenho do comprimento total da medida. O campo seguinte apenas modifica a distância com que esse desenho será feito em relação ao local da medida original.&#x20;

![](https://lh4.googleusercontent.com/kJ0DlO5uO2Y\_Hu6RSlEJYfc-CF4lB92iQF1aCsGPKCZ-C3kvIdOdoDXH6Er0O0h925HySHw92LTFcLAqD\_hCWkT9yMbnrYC5TQbvUt5miaJnNURAZ7it32zOGH-nPhCJ45TwjPj9jJz32kuRyA)
