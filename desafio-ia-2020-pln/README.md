# Desafio IA 2020 - Etapa PLN #
### Organized by: Rede de Especialistas - Grupo PLN ###
Starts on: Aug 28, 2020 11:59:59 PM
Ends on: Sep 18, 2020 11:59:59 PM 

[EvalAI Challenge Page](http://evalai.dev.serpro/web/challenges/challenge-page/15/overview)

## Challenge Overview ##

### Objetivo ###

O objetivo deste desafio é identificar emoções em textos escritos em português do Brasil. Por exemplo, identificar que a mensagem "américa latina é região mais atingida pela nova gripe, diz oms" sugere a emoção "medo". 

### Sobre o conjunto de dados ###

O conjunto de dados de [textos para análise de emoções](http://google.com/notfound) consiste de 1700 textos escritos em português do Brasil. Para cada texto existe uma classe que representa a principal emoção identificada no texto (alvo).

As 7 emoções possíveis e suas respectivas frequências na base disponibilizada são:

Emoção | Quantidade de textos
------------ | -------------
Alegria | 156
Desgosto | 223
Medo | 189
Neutro | 461
Raiva | 70
Surpresa | 214
Tristeza | 387

O objetivo deste desafio é identificar a principal emoção de cada texto.

As colunas neste conjunto de dados são:

* id String: identificação do texto
* texto String: Texto escrito em português do Brasil
* classe String: Principal emoção do texto

Além dos 1700 textos desse conjunto de dados, também é disponibilizado um outro conjunto de dados com 300 textos, sem as respectivas classes, para aplicação do método classificador implementado, gerando resultado que será submetido à avaliação.

Portanto, os dados foram divididos em dois conjuntos:

* Conjunto de treinamento (1700 textos)(treino.csv)
* Conjunto de testes (300 textos)(teste-sem-texto.csv)

O conjunto de treinamento deve ser usado para construir seus modelos de aprendizado de máquina. Para o conjunto de treinamento, fornecemos o resultado (também conhecido como a “verdade fundamental”) para cada texto (neste caso, a principal emoção - campo classe). Seu modelo de classificação de emoção será baseado no atributo texto.

O conjunto de testes deve ser usado para medir o desempenho do seu modelo em dados desconhecidos. Para o conjunto de testes, não fornecemos a verdade fundamental para cada observação (neste caso, a principal emoção do texto). É seu trabalho predizer esses resultados. Para cada texto do teste, use o modelo que você treinou para inferir qual das sete emoções existentes é a predominante no texto.

Também incluímos o arquivo submissao-exemplo.csv, um conjunto de previsões fictício (com resultados aleatórios), como um exemplo de como deve ser um arquivo de envio (submissão) a ser automaticamente avaliado. Esse arquivo possui apenas dois campos: id (identificação do texto) e classe (principal emoção do texto).

### Acesso aos dados ###

Acesse o conjunto de dados de [textos para análise de emoções](http://google.com/notfound)

### Cronograma do desafio ###

* Fase 1 - Inscrição: 24/08/2020 a 27/08/2020
* Fase 2 - Submissão: 31/08/2020 a 11/09/2020
* Fase 3 - Homologação do resultado: 14/09/2020 a 18/09/2020

### Baseline ###

O Grupo de Processamento de Linguagem Natural da [Rede de Especialistas em IA](https://sites.google.com/serpro.gov.br/datascience/intelig%C3%AAncia-artificial/rede-de-especialistas-em-ia) preparou um [Jupyter notebook](http://google.com/notfound) para demonstrar uma solução básica que envolve treinamento e teste com os dados disponibilizados. A pontuação obtida pelo modelo gerado nesse notebook é o baseline do leaderboard deste desafio. Ou seja, submissões com pontuações inferiores ao baseline não serão classificadas. 

### Perguntas mais frequentes ###

[Acesse](https://sites.google.com/serpro.gov.br/desafio-ia-2020-faq/in%C3%ADcio)

### Comissão organizadora ###

* Marcelo Pita (SUPAI)
* Carlos Machado (SUPAI)
* Luis Brito (SUPAI)
* José Guilherme Wasner (SUPAI)
* Rafael Odon (SUPAI)
* Sebastião Borges Fonseca (SUPAI)
* Fabrício Dalapola (SUPAI)
* José Maria Leocádio (SUPAI)
* Thiago D'Avila (SUPAI)
* Sérgio Dias (SUPAI)
* Maria Beatriz Silva (SUPED)
* Dayana Sousa (SUPED)
* Marcia Santos (SUPED)
* Sérgio Carvalho (DIDES/COADM)
* Victor Frederico Silva(SUPAI)

### Referências: ###

[Programa de Pós-Graduação em Informática](http://www.ppgia.pucpr.br/) da [Pontifícia Universidade Católica do Paraná](http://www.pucpr.br/)
