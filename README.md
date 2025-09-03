***
<div align=center>

![2025.09.03  ](https://img.shields.io/badge/2025.09.03-000000)

[![GitHub     ](https://img.shields.io/badge/-000000?logo=github&logoColor=FFFFFF)](https://github.com/kauefs/)
[![Medium     ](https://img.shields.io/badge/-000000?logo=medium&logoColor=FFFFFF)](https://medium.com/@kauefs)
[![LinkedIn   ](https://img.shields.io/badge/in-0077B5?logo=linkedin&logoColor=FFFFFF)](https://www.linkedin.com/in/kauefs/)

<a    href=https://materiais.indicium.ai/lighthouse_inscricao_turma-09_2025 target=_blank rel=noreferrer>
<img   src=https://d335luupugsy2.cloudfront.net/cms/files/212294/1754657899/$87ymsgkrln width=50%/></a>
</div>

# indicium

## Lighthouse

Programa Lighthouse de Formação em Dados e IA para profissionais em início ou em transição de carreira para a área de dados e IA, com projetos reais e desafiadores, aplicando conhecimentos na prática com suporte e mentoria de especialistas, mergulhando em tecnologias e metodologias de ponta para entender demandas de mercado.

### About the Company

**Indicium:** empresa global de serviços de dados, oferecendo soluções de ponta a ponta para todos os desafios da jornada data-driven, desde a estratégia à execução. Com sede em Nova York, São Paulo e Florianópolis, mais de 7 anos de experiência em metodologias modernas de dados e equipe de mais de 300 especialistas certificados, oferecendo serviços de alta qualidade, agnósticos e personalizados, atendendo aos mais altos padrões da indústria, encorajando busca contínua por novas e melhores ferramentas, e desenvolvendo as próprias, quando necessário.

**Missão:** ajudar clientes a modernizar e a escalar seus negócios para futuro data-driven.

**Visão:** ser o parceiro de dados moderno nº 1 para empresas nas Américas, reconhecido por oferecer qualidade incomparável e alto impacto mensurável para clientes.

**Valores:**
1. Qualidade:     criação de soluções de qualidade para resultados de alto valor.
2. Flexibilidade: adaptação a novos desafios e circunstâncias.
3. Colaboração:   colaboração por natureza
4. Transparência: gestão ética e transparente.
5. Conhecimento:  gosto por aprender e por ensinar.

***

## Desafio Cientista de Dados

**Situação:** análise de banco de dados cinematográfico para orientar estúdio de produção cinematográfico sobre o próximo tipo de filme a ser desenvolvido, com análise detalhada, levando em consideração o máximo de fatores possíveis, uma vez que há muito dinheiro envolvido.

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
   - database.csv

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
* Star1: ator/atriz #1
* Star2: ator/atriz #2
* Star3: ator/atriz #3
* Star4: ator/atriz #4
* No_of_Votes: número de votos
* Gross: faturamento

---

### Projeto

Projeto desenvolvido em Jupyter Notebook via plataforma Google Colab, podendo ser acessado diretamente pelo link: https://github.com/kauefs/indicium/blob/main/LH_DS_NOTEBOOK.ipynb
