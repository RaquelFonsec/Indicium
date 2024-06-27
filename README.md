# 🎬 Projeto de Análise Cinematográfica para PProductions

Este projeto utiliza análise de dados e modelos preditivos para orientar o desenvolvimento de filmes para o estúdio de Hollywood PProductions.

## 📂 Clonagem e Instalação

Clone o repositório e instale os pacotes necessários:


```bash
git clone https://github.com/RaquelFonsec/Indicium2.git
cd Indicium2
pip install -r requirements.txt



📊 Análise Exploratória de Dados (EDA)
O caderno Indicium(1).ipynb contém uma análise detalhada das variáveis ​​do conjunto de dados, explorando fatores que podem influenciar o sucesso de um filme.


❓ Perguntas respondidas
Filme Recomendado : "O Poderoso Chefão" foi recomendado devido à sua alta classificação no Meta Score e apelo universal nos gêneros de crime e drama.


Principais Fatores de Sucesso : A alta expectativa de faturamento está relacionada com classificação elevada crítica (Meta Score), arrecadação bruta (Gross) e o gênero do filme, como ação e comédia.


Insights da Coluna Overview : A sinopse pode inferir o gênero do filme, destacando temas predominantes como drama, ação ou comédia.

🎯 Previsão da Nota do IMDb
Utilizamos um modelo de Regressão Linear para prever a nota do IMDb do filme 'The Shawshank Redemption', considerando variáveis ​​como ano de lançamento, duração, Meta Score, entre outras.


Variáveis ​​Utilizadas e Transformações:
Números: Ano de lançamento, duração, Meta Score, número de votos, arrecadação.


Categóricas: Classificação indicativa, gênero, diretor e principais atores.


Transformações: Padronização para variáveis ​​numéricas e coincidência one-hot para variáveis ​​categóricas.


Modelo Escolhido:
A regressão Linear foi selecionada pela simplicidade e interpretabilidade, adequada para capturar relações lineares entre as variáveis ​​e a nota do IMDb.


Prós: Simplicidade, interpretabilidade, aplicação direta.
Contras: Limitado para relações não lineares complexas.

Medida de Desempenho:
Utilizamos o coeficiente de determinação ( R² ) para avaliar bem o modelo se ajustar aos dados observados.

Resultado:
O modelo anterior à nota do IMDb para ‘The Shawshank Redemption’ como 9.30, próximo à nota real de 9.3, mostrando que a abordagem foi eficaz na previsão da avaliação do filme.


📝 Conclusão
Este projeto oferece uma análise completa e preditiva para entender e prever o sucesso de filmes, utilizando técnicas avançadas de análise de dados. A análise exploratória fornece insights profundos e a modelagem preditiva recomenda estratégias para futuros desenvolvimentos cinematográficos.

Para mais detalhes, consulte o caderno Indicium(1).ipynb os resultados detalhados das análises estatísticas e preditivas.





