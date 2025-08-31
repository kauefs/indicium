# indicium
LightHouse
<!--
**Situação:** análise de banco de dados cinematográfico para orientar qual tipo de filme deve ser o próximo a ser desenvolvido, lembrando que há muito dinheiro envolvido, portanto a análise deve ser detalhada, levando em consideração o máximo de fatores possíveis.

**Objetivo:** resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos.

**Entregas:**
1. Análise Exploratória de Dados (EDA)
2. Ponderações:
   - Filme a se recomendar a uma pessoa desconhecida
   - Principais fatores relacionados à alta expectativa de faturamento de um filme
   - Insights da columa *Overview* e possibilidade de inferir o gênero do filme a partir dessa coluna
3. Modelagem de Nota do IMDb
4. Previsão  de Nota do IMDb para o seguinte filme:

        {'Series_Title':'The Shawshank Redemption',
         'Released_Year':'1994',
         'Certificate':'A',
         'Runtime':'142 min',
         'Genre':'Drama',
         'Overview':'Two imprisoned men bond over a number of years, finding solace and eventual redemption through acts of common decency.',
         'Meta_score':80.0,
         'Director':'Frank Darabont',
         'Star1':'Tim Robbins',
         'Star2':'Morgan Freeman',
         'Star3':'Bob Gunton',
         'Star4':'William Sadler',
         'No_of_Votes':2343110,
         'Gross':'28,341,469'}

5. Modelo salvo em formato .pkl
6. Repositório de código público:
   - README.md
   - requirements.txt
   - notebook.ipynb
   - model.pkl

**Dicionário dos Dados**

A base de dados de treinamento contém 15 colunas cujos nomes, embora auto-explicativos, são descritos a seguir:
* Series_Title: nome do filme
* Released_Year: ano de lançamento
* Certificate: classificação etária
* Runtime: tempo de duração
* Genre: gênero
* IMDB_Rating: nota do IMDb
* Overview: overview do filme
* Meta_score: média ponderada de todas as críticas 
* Director: diretor
* Star1: ator/Atriz #1
* Star2: ator/Atriz #2
* Star3: ator/Atriz #3
* Star4: ator/Atriz #4
* No_of_Votes: número de votos
* Gross: faturamento
