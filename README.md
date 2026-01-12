# ⚽ Brasileirão Série A 2009 — Análise de Dados

## 📌 Sobre
Este projeto realiza uma análise exploratória e estratégica do Campeonato Brasileiro de 2009. A partir de dados brutos das 380 partidas daquela edição, a análise busca entender a relação entre o desempenho esportivo, o comportamento das torcidas (engajamento) e o perfil da arbitragem. O projeto demonstra o ciclo completo de um analista de dados: desde a limpeza e tratamento até o storytelling visual.

## 📁 Dados
Os dados originais consistem em registros de partidas com informações de placar, estádios, horários, público e cartões. Durante o projeto, os dados foram **enriquecidos** através de:
- Cálculo de pontuação e criação de tabelas de classificação (turnos e geral).
- Conversão e normalização de horários e datas.
- Cruzamento de dados de bilheteria com performance em campo.

## 🛠️ Tecnologias
- **Python:** Linguagem base.
- **Pandas:** Manipulação, limpeza e engenharia de atributos.
- **Matplotlib & Seaborn:** Criação de visualizações avançadas e análise de tendências.
- **Jupyter Notebook:** Ambiente de desenvolvimento e documentação.

## 🚀 Como usar
1. Clone este repositório: `git clone https://github.com/LFM07/Projeto-Serie-A-.git`
2. Instale as dependências: `pip install pandas matplotlib seaborn`
3. Execute os notebooks na ordem numérica:
   - `01_limpeza_e_tratamento.ipynb`: Tratamento inicial e remoção de ruídos.
   - `02_tabela_e_desempenho_esportivo.ipynb`: Criação da tabela mestre e cálculos esportivos.
   - `03_analise_de_engajamento_e_graficos.ipynb`: Geração de gráficos e insights de engajamento.
   - `04_conclusoes_e_apresentacao_final.ipynb`: Resumo executivo dos resultados.

## 🧠 Resultados e Insights
- **O Fator Torcida:** Identificamos que o Flamengo e o Atlético-MG possuíam as maiores taxas de "Fidelidade Proporcional", mantendo estádios lotados independentemente da oscilação na tabela.
- **Eficiência por Horário:** Os jogos realizados aos **Domingos às 16h** apresentaram uma média de público significativamente superior, validando o impacto do horário nobre na arrecadação dos clubes.
- **Disciplina e Arbitragem:** Criamos um ranking dos árbitros mais rigorosos do campeonato, correlacionando o total de expulsões por partida.
- **Análise de Evolução:** O título de 2009 foi explicado estatisticamente pela curva de evolução do Flamengo no segundo turno, superando a média de pontos dos líderes da primeira fase.

## ⚙️ Próximos passos
- **Série Histórica:** Comparar os dados de 2009 com edições mais recentes (ex: 2023/2024) para analisar a evolução do público no Brasil.
- **Automação:** Desenvolver um script que colete dados via API de resultados em tempo real.
- **Dashboard:** Migrar as visualizações para um dashboard interativo no Streamlit ou Power BI.

## 📚 Fontes
- Dados históricos de campeonatos brasileiros (base CSV).
- Documentação oficial da CBF (referências de horários e arbitragem).

Essas colunas foram adicionadas manualmente e representam um esforço de enriquecimento da base de dados, tornando as futuras análises mais completas e realistas. O processo envolveu coleta, padronização e integração das informações no arquivo CSV principal do projeto.

Durante a fase de coleta e limpeza, identifiquei 2 partidas (ID 3082 e ID 3086) cujos dados de público não estavam disponíveis em fontes públicas e oficiais. Para manter a integridade estatística, esses valores foram tratados como 0 (ou excluídos das médias de público) para não enviesar a análise dos clubes envolvidos.
