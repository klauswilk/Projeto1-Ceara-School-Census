# Projeto1-Ceara-School-Census
Repositório de projeto referente ao Censo Escolar do Estado do Ceará (Brasil).

Abaixo, segue o link do vídeo explicando as análises realizadas no dashboard e um breve resumo do projeto:

https://youtu.be/vyi870hr8Ws


A ideia inicial do projeto era realizar a análise exploratória de dados (i.e. uma 
abordagem à análise de conjuntos de dados de modo a resumir suas características 
principais) do Censo escolar do Brasil, especificamente, do ano de 2019.
Todavia, o banco de dados escolhido possuía uma grande quantidade de informações 
com complexos relacionamentos, dificultando a análise e o tratamento destes 
dados. 
Nesse contexto, foi escolhido o banco de dados do Censo escolar do Ceará, que foi 
obtido na plataforma kaggle.

Após as primeiras análises foi identificada a necessidade de incluir mais uma tabela, 
pois o banco de dados do Censo escolar não possuía informações referentes aos 
nomes dos municípios, regiões, latitude e longitude, tendo somente os seus 
respectivos códigos identificadores.
Portanto, a tabela com o nome DTB_MUNICIPIOS_IBGE foi incluída no projeto. Ela foi 
obtida na plataforma do IBGE. 
Além disso, a TABELA_CALENDARIO foi criada com o intuito de otimizar a obtenção 
de informações das datas, porque essa tabela é bem menor, em comparação ao 
banco de dados principal.
O banco de dados principal é o ESCOLAS_CE
