# Estudo sobre o conteúdo da Netflix até 2023

![URL da Imagem](https://github.com/caiombribeiro/estudo_netflix_2023/blob/main/exemplo/dashboard.jpg?raw=true)

O presente estudo tem como proposta trazer informações a respeito sobre o conteúdo disponibilizado pela NETFLIX. 

## 0. Motivação

![alt text](https://github.com/caiombribeiro/estudo_netflix_2023/blob/main/background/netflix.png?raw=true){width=300 height=180 }

A NETFLIX é uma das maiores plataformas de Streaming atualmente no mundo. Basicamente, é impossível lembrar do serviços de streaming sem lembrar da empresa, já que ela foi a grande pioneira na área.

Contudo, sem utilizar dados fica um tanto vago o tamanho da empresa em quesito de alcance. Por exemplo, como saber a quantidade de conteúdos em seu catálogo? Quais são os gêneros mais bem avaliados? E qual é a média de horas assistidas?

Foi pensando nessas perguntas que foi construida esse estudo.

## 1. Importação

Para fazer o estudo, foi utilizada como base de dados o arquivo em formato excel presente no Kaggle e nesse [Link](https://www.kaggle.com/datasets/willianoliveiragibin/netlifx-hour-2023).

Foi utilizado o Python para linguagem de programação e o pacote Pandas.

## 2. Transformação

A primeira etapa de transformação consiste em redefinir os tipos de cada coluna, para não gerar nenhum conflito com o software de visualização. 

Também foi removida as linhas de filmes que não possuiam a data de lançamento ou a quantidade de avaliações. É sabido que, por conta dessas exclusões, a análise não ficou 100% precisa, mas o ideal seria ter todos esses dados validos, por isso foi a melhor escolha.

Os dados de gênero estavam despadronizados dessa forma:

0	Biography, Drama, History
1	Comedy, Drama,Romance
2	['Short']
3	['Drama', 'History', 'Romance']
4	['Comedy', 'Romance']
...

Por isso, foi feito tanto a padronização quanto a separação de gêneros em mais colunas para ficar melhor disposto esses dados e facilitar o trabalho futuro.

Por fim, foi renomeado cada atributo para melhor descrição das colunas.


## 3. Geração do arquivo

O arquivo aqui foi gerado em excel para posterior importação.

## 4. Visualização

Para visualização, foi utilizado o Power Bi da Microsoft por sua versatilidade. Disponibilizei o arquivo com formato .pbix aqui no GitHub para download.

Por questão de facilidade, foi trabalhado o arquivo excel dentro do Power BI utilizando sua versão longa em relação ao gêneros, pois achei melhor fazer uma análise contabilizando todos os gêneros em uma única coluna.

Os gráficos utilizados foram decididos de acordo com as perguntas chave trazidas anteriormente. 

## 5. Conclusão

Com o dashboard pronto, foi possivel responder algumas questões, tais como:

- Total de conteúdo presente: + 15 mil
- Total de horas assistidas em 2023: 118,40 Bilhões
- Quais os gêneros com mairo nº de conteúdos: Comédia e Drama
- Qual o gênero de conteúdo mais bem avaliado em 2023: Talk-Show

Ainda é possivel ter mais insights, o que ajudaria uma produtora de conteúdo saber qual o tipo de conteúdo que mais desejam ver na plataforma. 

Obviamente, eu utilizei apenas uma base de dados do kaggle. Mas, se fosse um estudo sério, poderá ser utilizado as bases diretamente informadas de mais de 1 plataforma para fazer o comparativo entre elas inclusive.