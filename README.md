<h1 align="center">Criação de Métricas para Varejo </h1>

<p align="center">
 <a href="#entendimento-do-negócio">Entendimento do negócio</a> •
 <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a> •
 <a href="#tratamento-dos-dados">Tratamento dos dados</a> • 
 <a href="#entendimento-dos-dados">Entendimento dos dados</a> • 
 <a href="#perguntas-de-negócio">Perguntas de negócios</a
</p>

## Entendimento do negócio

<p align="justify"> Esta é uma proposta de resolução para um case de um encontro ao vivo da Formação em Dados da Escola DNC. Trata-se da criação de uma série de métricas para acompanhamento de resultados de uma empresa de varejo on-line que vende produtos eletrônicos de alta qualidade.

<p align="justify"> A empresa possuía uma base de dados contendo informações sobre datas de envio e chegada de produtos, quantidade de ligações feitas, custo e peso do produto, desconto, atraso na entrega entre outras informações menos relevantes para o case.

<p align="justify"> Foram solicitadas métricas sobre custos das ligações feitas, custo dos produtos, comportamento do custo do produto pela data de entrega, desconto por preço do produto e correlações entre variáveis.

## Tecnologias utilizadas
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn

## Tratamento dos dados
Para utilizarmos as informações de maneira ideal, foi necessário fazer a manipulação da base de dados. Destaca-se:
- Remoção de linhas com valores nulos
- Correção dos tipos de dados

## Entendimento dos dados
<p align="justify"> Foi feita a análise univariada para observar a distribuição de frequência das variáveis categóricas e a distribuição de variáveis numéricas (média, mínimo, máximo, desvio padrão), afim de procurar por padrôes ou tendências relevantes para o negócio.

## Perguntas de negócio
<p align="justify"> 
Para criação das métricas solicitadas, foram utilizadas técnicas de agrupamento de dados e gráficos para visualização. A partir das informações levantadas, observou-se que:

- <div align="justify"> A medida que o número de ligação aumenta, o custo médio do produto também aumenta. Em termos de soma total e percentual dos custos, a maior parte dos valores concentra-se entre 3 e 5 ligações. Essa informação nos permite entender o impacto das ligações, possibilitando atrelar metas relacionadas à elas. 

<p align="center">
    <img width="700" height="400" src="https://github.com/viniciusendo/Mais_Metricas_Varejo/assets/134152277/86f8c33b-9baa-41aa-ade0-470945e5fcda">
</p>

- O custo dos produtos concentra-se em valores 150 e 270. Essa informação nos permite enteder a distribuição dos valores dos produtos vendidos.

<p align="center">
    <img width="420" height="240" src="https://github.com/viniciusendo/Mais_Metricas_Varejo/assets/134152277/b454777b-2dc7-4525-8426-ed01cf958507">
</p>

- O custo do produto não apresenta grandes variações em relação à data de entrega.

<p align="center">
    <img width="420" height="240" src="https://github.com/viniciusendo/Mais_Metricas_Varejo/assets/134152277/9d1c2e64-bf18-4d17-a2eb-cf45eb68cd62">
</p>

- <div align="justify"> Produtos entregues sem atraso tem um valor de desconto máximo bem menor que produtos entregues com atraso. Essa informação reforça a necessidade de realizar entregas nos prazos acordados, para que as vendas não sejam impactadas negativamente.

<p align="center">
    <img width="400" height="320" src="https://github.com/viniciusendo/Mais_Metricas_Varejo/assets/134152277/4e64ee4f-f0ba-4258-8220-84722425f83a">
</p>

- Existe uma pequena correlação entre desconto e atraso na entrega e entre quantidade de ligações feitas e custo do produto. Essa informação é importante para ajudar a entender relações entre partes do processo.

<p align="center">
    <img width="600" height="400" src="https://github.com/viniciusendo/Mais_Metricas_Varejo/assets/134152277/4167d634-c042-4b71-8f0b-fd94a020b717">
</p>


