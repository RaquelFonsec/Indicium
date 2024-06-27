Análise Cinematográfica para PProductions
Este projeto visa utilizar análise de dados e modelos preditivos para orientar qual tipo de filme deve ser o próximo a ser desenvolvido para o estúdio de Hollywood PProductions.

Descrição
O projeto envolve uma análise detalhada sobre um banco de dados cinematográfico, considerando diversos fatores que podem influenciar o sucesso de um filme. A análise exploratória de dados, respostas às perguntas propostas e a modelagem preditiva são partes essenciais deste desafio.

Como clonar e instalar o projeto
Clone o repositório em sua máquina local utilizando o seguinte comando:

git clone https://github.com/RaquelFonsec/Indicium2.git
cd Indicium2

Instalação de Pacotes:

pip install -r requirements.txt

Análise Exploratória dos Dados (EDA)
O notebook copy_Indicium.ipynb contém a análise exploratória dos dados, onde são exploradas as principais características entre as variáveis do dataset. São apresentadas hipóteses relacionadas aos fatores que influenciam o sucesso de um filme.

Perguntas respondidas
Qual filme você recomendaria para uma pessoa que você não conhece?

Com base na análise, o filme recomendado seriado “O Poderoso Chefão”, devido à sua alta pontuação no Meta Score e seu apelo universal nos gêneros de crime e drama.

Quais são os principais fatores que estão relacionados com a alta expectativa de faturamento de um filme?

Os principais fatores incluem classificação crítica elevada (Meta Score), arrecadação bruta (Gross) e o gênero do filme, com certos gêneros como ação e comédia tendo um desempenho melhor em bilheterias

Quais insights podem ser tirados com a coluna Visão geral? É possível inferir o gênero do filme a partir dessa coluna?

A Overview fornece uma sinopse que pode ser utilizada para inferir o gênero do filme. Palavras-chave na sinopse podem indicar o tom e o tema predominante, como drama, ação ou comédia.

Previsão da nota do IMDb a partir dos dados

Foi um modelo de regressão proposto para prever a nota do IMDb com base em características como ano de lançamento, duração do filme, classificação no Meta Score, entre outras. Modelos como Regressão Linear foram expl

Conclusão
Este projeto oferece uma abordagem completa para analisar e prever o sucesso de filmes, utilizando técnicas avançadas de análise de dados e modelagem preditiva. A análise exploratória dos dados fornece insights profundos sobre os fatores determinantes do sucesso cinematográfico, enquanto a modelagem preditiva ajuda a recomendar estratégias para futuros desenvolvimentos do filme

Para mais detalhes, consulte o notebook copy_Indicium.ipynb e os resultados detalhados das análises estatísticas e preditivas.
