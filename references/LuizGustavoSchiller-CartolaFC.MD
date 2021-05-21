CartolaFC
Data from the popular Brazilian Fantasy Football (2014 to 2017) ⚽️

https://www.kaggle.com/schiller/cartolafc

Context
CartolaFC is the most popular fantasy football in Brazil. Before each round of the Brazilian Football League, players choose which athletes they want for their teams, and they score points based on their real-life performances.

Content
Data is divided in 7 kinds of files:

Athletes (atletas)

"atleta_id": id,

"nome": athlete's full name,

"apelido": athlete's nickname

Clubs (clubes)

"id": id,

"nome": club's name,

"abreviacao": name abbreviation,

"slug": used for some API calls

Matches (partidas)

"rodada_id": current round,

"clubecasaid": home team id,

"clubevisitanteid": away team id,

"clubecasaposicao": home team's position on the league,

"clubevisitanteposicao": away team's position on the league,

"aproveitamento_mandante": home team's outcome on the last five matches (d: loss, e: draw, v: victory),

"aproveitamento_visitante": away team's outcome on the last five matches (d: loss, e: draw, v: victory),

"placaroficialmandante": home team's score,

"placaroficialvisitante": away team's score,

"partida_data": match date,

"local": stadium,

"valida": match valid for scoring

Scouts

"atleta_id": reference to athlete,

"rodada_id": current round,

"clube_id": reference to club,

"posicao_id": reference to position,

"status_id": reference to status,

"pontos_num": points scored on current round,

"preco_num": current price,

"variacao_num": price variation from previous round,

"media_num": average points per played round,

"jogos_num": number of matches played,

"FS": suffered fouls,

"PE": missed passes,

"A": assistances,

"FT": shots on the post,

"FD": defended shots,

"FF": shots off target,

"G": goals,

"I": offsides,

"PP": missed penalties,

"RB": successful tackes,

"FC": fouls commited,

"GC": own goals,

"CA": yellow cards,

"CV": red cards,

"SG": clean sheets (only defenders),

"DD": difficult defenses (only goalies),

"DP": defended penalties (only goalies),

"GS": suffered goals (only goalies)

Positions (posicoes)

"id": id,

"nome": name,

"abreviacao": abbreviation

Status

"id": id,

"nome": name

Points (pontuacao)

"abreviacao": abbreviation,

"nome": name,

"pontuacao": points earned for respective scout

Acknowledgements
The datasets from 2014 to 2016 were taken from here: https://github.com/thevtm/CartolaFCDados.

Data from 2017 until round 11 was taken from this repo: https://github.com/henriquepgomide/caRtola.

From 2017 round 12 and on, I've been extracting the data from CartolaFC's API (which is not officially public).

Inspiration
It would be interesting to see analyses on which factors make an athlete or team more likely to score points, and also predictive models for future scores.