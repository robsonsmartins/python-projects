# INFORMAÇÕES GERAIS SOBRE A SOLUÇÃO
## Nome da solução
Analisador de Desempenho do PBF 
## Descrição resumida
Ambiente de análise da efetividade da aplicação/execução do Programa Bolsa Família (PBF)
## Descrição detalhada
Este trabalho tem por finalidade demonstrar um ambiente para análise de desempenho e eficácia do PBF, a partir de cruzamento de dados e predição (baseada em regressão linear).

Apesar de ter como foco o PBF, este ambiente de análise pode ser aplicado para outros conjuntos de dados, de forma semelhante.
## Qual o cliente-alvo?
Ministério do Desenvolvimento Social (http://mds.gov.br) [considerando a atual estrutura ministerial em 2018].
## Qual o público-alvo?
- [**Direto**] Governo Federal (gestor dos recursos);
- [**Indireto**] Cidadão participante do Programa (beneficiário dos recursos);
- [**Indireto**] Cidadão contribuinte (provedor dos recursos).

# INFORMAÇÕES DE NEGÓCIO DA SOLUÇÃO
# Artefatos de negócio

| Artefato | Caminho do arquivo |
| --- | --- |
| Pitch | https://github.com/robsonsmartins/python-projects/blob/master/desafio-inova-2018/doc/equipe148-pitch.mp4 |
| Business Model Canvas (BMC) | https://github.com/robsonsmartins/python-projects/blob/master/desafio-inova-2018/doc/equipe148-bmc.pdf |
| Blueprint da solução | https://github.com/robsonsmartins/python-projects/blob/master/desafio-inova-2018/doc/equipe148-blueprint.pdf |

# INFORMAÇÕES TÉCNICAS DA SOLUÇÃO
## Ferramentas utilizadas
Informe quais ferramentas foram utilizadas para a construção da solução (marcar um "X" na primeira coluna e especificar a *Versão*):

|    | Ferramenta        | Versão |
| -- | ----------------- | ------ |
| X  | a) Jupyter        |  5.7   |
|    | b) RStudio        |        |
|    | c) Zeppelin       |        |
|    | &lt;Outra (especificar)&gt; |      |

## Linguagens de programação utilizadas
Informe quais linguagens de programação foram utilizadas no desenvolvimento da solução
(marcar um "X" na primeira coluna e especificar a *Versão*):

|    | Linguagem         | Versão |
| -- | ----------------- | ------ |
| X  | Python | 3.6 |
|    | R |   |
|    | Scala |   |
|    | Java |  |
|    | C/C++ |   |
|    | &lt;Outra (especificar)&gt; |   |

## Forma de disponibilização da solução
Informe como a solução funcional pode ser acessada tanto para fins de avaliação do *Desafio de Inovação* quanto para a posterior disseminação do conhecimento na empresa. **Atenção: para a avaliação do _Desafio de Inovação_, a solução funcional deve estar disponível no período de 26 de novembro a 05 de dezembro de 2018.**

|    | Forma de disponibilização | Localização | Usuário | Senha |
| -- | ----------------- | --- | --- | --- |
| X  | Documento Notebook (src) | https://github.com/robsonsmartins/python-projects/blob/master/desafio-inova-2018/src/equipe148.ipynb | N/A | N/A |
| X  | Documento Notebook (pdf) | https://github.com/robsonsmartins/python-projects/blob/master/desafio-inova-2018/src/equipe148.pdf | N/A | N/A |
|    | Script em linha de comando | N/A | N/A | N/A |
|    | Aplicação web [3] | N/A |  |  |
|    | Ferramenta analítica | N/A |  |  |
|    | Outra forma (especificar) | N/A |  |  |

# Bases de dados utilizadas
Informe quais bases de dados foram utilizadas na solução (marcar um "X" na primeira coluna e especificar quais informações dessas foram usadas):

|    | Base de dados     | Informações utilizadas (especificar os nomes das tabelas) |
| -- | ----------------- | ------------------------------ |
|    | a) Nota Fiscal Eletrônica - NF-e |  |
|    | b) Estatísticas de comércio exterior - Comex Stat |  |
|    | c) Quadros societários e de administradores das pessoas jurídicas |  |
|    | d) Compras governamentais - Compras sem licitação |  |
|    | e) Transferências voluntárias da União (convênios) - SICONV |  |
|    | f) Transferências constitucionais para estados e municípios |  |
| X  | g) Pagamentos do Programa Bolsa Família - PBF | pagamentos[ver NOTA] |
|    | h) Prestações de contas de campanhas eleitorais |  |
|    | i) Exame Nacional do Ensino Médio |  |
|    | j) Censo da Educação Superior |  |
|    | k) Produto Interno Bruto dos municípios brasileiros |  |
|    | l) População estimada dos municípios brasileiros |  |
|    | m) Divisão político-administrativa dos territórios brasileiros |  |
| X  | n) Índice de Desenvolvimento Humano Municipal - IDHM | idhm1991, idhm2000, idhm2010 |
| X  | o) Outra Base: Pagamentos do Programa Bolsa Família (PBF) por Ano/Município | https://aplicacoes.mds.gov.br/sagi/vis/data/data-table.php |

NOTA: Por questões de performance nas consultas, e pelo período desejado para os dados na base, optou-se por utilizar uma base em CSV de pagamentos do PBF por ano e por município, obtido livremente no site especificado acima.

# Eixos de interesse aplicados
Informe quais eixos de interesse foram aplicados na solução (marcar um "X" na primeira coluna):

|    | Eixo de interesse |
| -- | ----------------- |
|    | a) Agrupamento (_clustering_) |
| X  | b) Análise de correlação |
| X  | c) Análise de séries temporais |
| X  | d) Análise de tendências |
| X  | e) Análise de vínculos |
|    | f) Aprendizado de máquina profundo (_deep learning_) |
| X  | g) Associação |
|    | h) Classificação |
|    | i) Detecção de anomalias |
|    | j) Mineração de textos |
|    | k) Processamento de Linguagem Natural (_Natural language processing - NLP_) |
|    | l) Redes neurais |
| X  | m) Regressão |

### Técnicas e/ou algoritmos aplicados
Informe quais técnicas e/ou algoritmos relacionados aos eixos de interesse escolhidos foram aplicados na solução (marcar um "X" na primeira coluna e especificar a localização do respectivo código no repositório Git):

|    | Eixo de interesse | Nome da técnica/algoritmo | Localização no código (caminho do arquivo : número da linha) |
| -- | ---- | ----------------- | ----------------- |
|  | Análise de correlação, tendências, vínculos | Associação, correlação amostral | equipe148.ipynb : In[9]:1  |
|  | Regressão, Análise de séries temporais | Regressão Linear | equipe148.ipynb : In[14]:27  |

## Assertividade do modelo
O modelo apresentou nível de assertividade dentro do esperado, considerando o conjunto (amostra) de dados fornecido para o treinamento da regressão linear e para as análises.

# INFORMAÇÕES SOBRE A EQUIPE
## Membros da equipe

| Nome completo | Lotação |
| ------------- | ------- |
| Robson de Sousa Martins | ---- |
