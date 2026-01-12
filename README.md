# Projeto-Serie-A-


Coletando mais informacoes que nao continham no csv que encontramos e recheando ainda mais o csv para trabalharmos aprofundamente no brasileirao de 2009

Sites que foram utilizados para coletar mais informacoes para o CSV:

https://www.bolanaarea.com/brasileirao_2009.htm: utilizamos esse site para coletar informacoes para as colunas de "publico_jogo", "juiz_partida", "expulsao_mandante","expulsao_visitante" e "dia_semana_jogo".

incluímos as colunas de formacao_mandante e formacao_visitante, porém as formações ainda não foram incluídas por limitações de coleta manual, mas estão planejadas para futura expansão do dataset.

### 🧩 Colunas adicionais criadas
Durante o processo de enriquecimento do dataset original, foram adicionadas novas colunas com o objetivo de permitir análises mais completas sobre o Brasileirão de 2009. Essas colunas não existiam na base original e foram coletadas manualmente a partir de fontes externas, como o site [Bola na Área](https://www.bolanaarea.com/brasileirao_2009.htm).

As novas colunas adicionadas foram:

publico_jogo

Representa o número de torcedores presentes em cada partida. Essa informação foi coletada individualmente e permite análises sobre o engajamento da torcida e a média de público por rodada, estádio ou dia da semana.

juiz_partida

Nome do árbitro responsável por apitar a partida. Essa coluna possibilita identificar padrões de arbitragem, frequência de atuação e possíveis correlações com o número de expulsões.

expulsao_mandante

Quantidade de jogadores expulsos do time mandante em cada jogo. Utilizada para avaliar a disciplina dos times e sua relação com o resultado da partida.

expulsao_visitante

Quantidade de jogadores expulsos do time visitante em cada jogo. Assim como a coluna anterior, ajuda em análises comportamentais e de arbitragem.

dia_semana_jogo

Indica o dia da semana em que a partida ocorreu (domingo, quarta, etc.). Essa informação foi adicionada para permitir análises temporais, como o impacto do dia da semana no público ou na performance dos times.

Essas colunas foram adicionadas manualmente e representam um esforço de enriquecimento da base de dados, tornando as futuras análises mais completas e realistas. O processo envolveu coleta, padronização e integração das informações no arquivo CSV principal do projeto.

Durante a fase de coleta e limpeza, identifiquei 2 partidas (ID X e ID Y) cujos dados de público não estavam disponíveis em fontes públicas e oficiais. Para manter a integridade estatística, esses valores foram tratados como 0 (ou excluídos das médias de público) para não enviesar a análise dos clubes envolvidos.