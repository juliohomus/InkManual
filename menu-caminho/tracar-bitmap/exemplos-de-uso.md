# Exemplos de uso



![License: CC0 Public Domain](<../../.gitbook/assets/image (3) (1) (2).png>)

1. Fazemos a primeira vetorização buscando traçar a silhueta da girafa e do solo. Vamos alterar apenas o limiar para algo próximo de 0,115.
2. Vamos agora realizar o traçado da luz do sol sobre as nuvens, usando _Inverter imagem_ e definindo o limiar próximo de 0,550
3. Vamos agora vetorizar apenas o sol. Repetindo o mesmo processo anterior, mas com limiar próximo de 0,950
4. Por fim, vamos usar [Diferença](../#diferenca) para remover recortar o sol dentro do clarão das nuvens.

Resultado final:No exemplo abaixo, temos a silhueta de uma girafa sobre um terreno e pássaros ao fundo. Vamos vetorizar esta imagem duas vezes para gerar um melhor resultado.

![](<../../.gitbook/assets/image (16).png>)

