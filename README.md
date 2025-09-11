# Desafio-Ifood: Análise Exploratória de Dados (AED)

Este projeto é um desafio prático do curso **Estatística do Básico ao Avançado (E.B.A.)**, realizado de forma independente como forma de aplicar e aprofundar os conhecimentos em **análise de dados** e **estatística descritiva**, utilizando a linguagem **Python** aprendidos até o momento do curso.


---

### Estrutura de Dados

O conjunto de dados é composto por **2.240 linhas e 29 colunas**, com uma variedade de dados numéricos, categóricos e binários. As principais colunas do dataset incluem:

* `ID`: Identificador único do cliente.
* `Year_Birth`: Ano de nascimento.
* `Education`: Nível de educação.
* `Marital_Status`: Estado civil.
* `Income`: Salário anual.
* `Kidhome`: Número de crianças em casa.
* `Teenhome`: Número de adolescentes em casa.
* `Dt_Customer`: Data de inscrição na empresa.
* `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`: Valores gastos em diferentes categorias de produtos nos últimos 2 anos.
* `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`: Número de compras realizadas por canal de venda.
* `AcceptedCmp1` a `AcceptedCmp5`: Aceitou ou não as campanhas de marketing.

---

### Metodologia da Análise Exploratória de Dados (AED)

O projeto foi desenvolvido em um **notebook Jupyter** pela ferramenta do Google Colab, onde a análise e visualização de dados foram realizadas de forma organizada. A metodologia seguiu etapas principais, refletidas na estrutura do notebook:

#### 1. Preparação e Carregamento de Dados

Nesta etapa, o foco foi inspecionar a integridade e a estrutura do conjunto de dados, com as seguintes ações:

* Importando o arquivo para o colab.
* Importando bibliotecas necessárias. 

#### 2. Visualizaçao dos Dados

Esta seção foi dedicada à visualização inicial dos dados, com as seguintes ações:

* Visualização da forma atual dos dados.
* Visualização das informações completa dos dados.

#### 3. Análise de Estrutura e Integridade

Esta seção foi dedicada a responder às primeiras perguntas do desafio, focando na estrutura e integridade do dataset:

* Quantos dados temos? Linhas e colunas 
* Quais são as colunas numéricas?
* Temos duplicados na nossa base? Se tivermos, retire-os 
* Temos dados nulos nessa base? Será que eles indicam algo? O que fazer com eles? 

#### 4. Análise Descritiva

Esta seção foi dedicada à análise estatística das colunas numéricas, com o cálculo de:

* Qual é a média, mediana, quartis, mínimo e máximo de cada uma das colunas numéricas?

#### 5. Análise do Perfil do Cliente

Esta seção aprofundou o entendimento sobre as características dos clientes, respondendo a perguntas como:

* Qual é o maior salário na base de dados?
* Qual é a distribuição de salários dos clientes?
* Qual é o nível de educação predominante?
* Quantos clientes existem em cada estado civil?

#### 6. Análise de Correlação

A etapa final consistiu em uma análise de correlação para identificar as relações entre as variáveis e obter insights sobre o comportamento de consumo. As correlações analisadas incluíram as seguintes perguntas:

* Qual é a relação de **estado civil** com número de **filhos**? Será que as pessoas **casadas** têm um maior número de **filhos**?
* As pessoas **gastam** mais ou menos em nossa plataforma quando têm **filhos**?
* Pessoas que têm um **maior salário** gastam mais?
