Cartola FC Brasil Scouts
Players performance, games results and casting stats from 2019 and 2020

https://www.kaggle.com/lgmoneda/cartola-fc-brasil-scouts/metadata

Dados do Cartola FC - PT-BR
Contexto
Assim como todo data scientist que conhece o Cartola, fiquei com vontade de criar modelos para escalar os times. Existem datasets já disponíveis (ver "Alternativas"), mas resolvi criar esse no Kaggle pra facilitar o compartilhamento com notebooks e também o uso de outros datasets, como o de notícias de esporte.

Conteúdo
Três conjuntos de dados para o ano de 2019 e 2020 (até a rodada mais atual):

Jogadores: contém a pontuação, preço e seus detalhes para cada rodada
Jogos: são os resultados dos jogos
Escalações: ranking de quais jogadores foram mais escalados em cada rodada
Detalhes
A pontuação é formada da seguinte mandeira (fonte: Cartola FC Brasil Scout)

SCOUTS POSITIVOS

DS - Desarme (+ 1,0)
G - Gol (+8,0)
A - Assistência (+5,0)
SG - Jogos sem Sofrer Gols (+5,0)
FS - Falta Sofrida ( +0,5)
FF - Finalização para Fora (+0,8)
FD - Finalização Defendida (+1,2)
FT - Finalização na Trave (+3,0)
DD - Defesa Difícil (+4,0)
DP - Defesa de Pênalti (+7,0)
SCOUTS NEGATIVOS

GC - Gol Contra (-5,0)
CV - Cartão Vermelho (-5,0)
CA - Cartão Amarelo (-2,0)
GS - Gol Sofrido (-2,0)
PP - Pênalti Perdido (-4,0)
FC - Falta Cometida (-0,5)
I - Impedimento (-0,5)
PI - Passe Incompleto (-0,1)
Mudança no RB
Segundo a UOL:

Sem roubada de bola
O nome agora é desarme, esqueça a famosa RB. E a pontuação vai de 1,5 para 1. Os jogadores não precisarão garantir a posse de bola para o seu time para pontuar. Agora, se cortar um passe, mesmo que a bola vá para fora, ele poderá pontuar.


escalacoes.csv
How many times a player was cast in the fantasy game for a particular championship round.

jogadores.csv
Players stats for every round.

jogos.csv
Resultado dos jogos para cada rodada