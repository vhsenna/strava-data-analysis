# Análise exploratória de dados pessoais no Strava

[Strava](https://www.strava.com) é uma rede social bastante utilizada por ciclistas profissionais e amadores, em competições, mas também no lazer e deslocamento por ciclistas urbanos, assim como eu.

Além de proporcionar que os usuários acompanhem os registros de amigos e ciclistas famosos, o Strava também permite traçar dados estatísticos de desempenho e outras curiosidades, como maior distância percorrida, velocidade média da corrida etc. Além disso, possui uma espécie de ranking em trechos criados pelos próprios usuários.

No meu caso particular, como faço uso diário da bicicleta desde 2012, decidi analisar estes dados encontrar alguns padrões de comportamento ao longo dos anos e curiosidades, além, claro, de responder diversas perguntas.

Primeiramente conectei meu usuário à API e fiz download dos dados, salvando-os num arquivo csv. O processo é bastante chato, mas consegui através de [um tutorial no Youtube](https://www.youtube.com/watch?v=sgscChKfGyg).

Após a extracão dos dados, tratei e limpei algumas ocorrências e, em seguida, plotei diversos gráficos utilizando as bibliotecas Matplotlib e Seaborn.
