<h1 align="center">DCN - Case Varejo - Encontro ao Vivo</h1>

<p align="center">
 <a href="#entendimento-do-negócio">Entendimento do negócio</a> •
 <a href="#tratamento-dos-dados">Tratamento dos dados</a> • 
 <a href="#entendimento-dos-dados">Entendimento dos dados</a> • 
 <a href="#perguntas-de-negócio">Perguntas de negócios</a> •  
 <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a
</p>

## Entendimento do negócio

<p align="justify"> Esta é uma proposta de resolução para um case de um encontro ao vivo da Formação em Dados da Escola DNC. Trata-se da criação de uma série de métricas para acompanhamento de resultados de uma empresa de varejo.

<p align="justify"> A empresa possuía uma base de dados contendo informações sobre datas de envio e chegada de produtos, quantidade de ligações feitas, custo e peso do produto, desconto, atraso na entrega entre outras informações menos relevantes para o case.

<p align="justify"> Foram solicitadas métricas sobre custos das ligações feitas, custo dos produtos, comportamento do custo do produto pela data de entrega, desconto por preço do produto e correlações entre variáveis

## Tratamento dos dados
Para utilizarmos as informações de maneira ideal, foi necessário fazer a manipulação da base de dados. Destaca-se:
- Remoção de linhas com valores nulos
- Correção dos tipos de dados

## Entendimento dos dados
<p align="justify"> Foi feita a análise univariada para observar a distribuição de frequência das variáveis categóricas e a distribuição de variáveis numéricas (mín, máx, desvio padrão), afim de procurar por padrôes ou tendências relevantes para o negócio.

## Perguntas de negócio
<p align="justify"> 
Para criação das métricas solicitadas, foram utilizadas técnicas de agrupamento de dados e gráficos para visualização. A partir das informações levantadas, observou-se que:

- <div align="justify"> A medida que o número de ligação aumenta, o custo médio do produto também aumenta. Em termos de soma total e percentual dos custos, a maior parte dos valores concentra-se entre 3 e 5 ligações
- O custo dos produtos concentra-se em valores 150 e 270
- O custo do produto não apresenta grandes variações em relação à data de entrega
- Produtos entregues sem atraso tem um valor de desconto máximo bem menor que produtos entregues com atraso
- Existe uma pequena correlação entre desconto e atraso na entrega e entre quantidade de ligações feitas e custo do produto

## Tecnologias utilizadas
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
