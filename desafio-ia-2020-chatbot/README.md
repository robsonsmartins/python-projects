# Desafio IA 2020 - Etapa PLN e Chatbots #
### Organized by: Rede de Especialistas ###
Starts on: Nov 23, 2020 08:00:00 AM
Ends on: Dec 04, 2020 06:00:00 PM 

[Kaggle Challenge Page](https://www.kaggle.com/c/desafio-ia-2020-pln-chatbots)

## Challenge Overview ##

### Descrição do desafio ###

O objetivo deste desafio é construir um orquestrador de chatbots, que poderá servir de base para um sistema real do Serpro.

O participante deverá prever para qual chatbot uma determinada pergunta (ou frase) será direcionada. Ou seja, o objetivo do desafio é criar um modelo (ou modelos) que classifique(m) perguntas de acordo com os chatbots relacionados.

Para tal, será disponibilizada aos participantes uma base de treinamento com diversas perguntas previamente rotuladas, e que pertencem a diferentes chatbots desenvolvidos no Serpro.
Será ainda disponibilizada uma base com uma série de perguntas não rotuladas, que deverão ser classificadas pelo(s) modelo(s) construído(s) e cujos resultados serão submetidos para avaliação.

Um dificultador importante, para o qual os participantes devem atentar: é perfeitamente possível existir, na base não classificada, perguntas não relacionadas com nenhum dos chatbots. Ou seja, serão perguntas imprevistas, fora do contexto englobado. Essas perguntas, se identificadas como tais, deverão ser rotuladas com um "0" (zero). Fique atento: ainda que tais perguntas sejam minoria, elas estarão em número suficiente para fornecer uma vantagem adicional aos participantes que conseguirem classificá-las.

Leia com cuidado o regulamento do desafio, para não usar ferramentas, práticas ou serviços não permitidos.

Em caso de dúvidas, é possível usar a seção "Discussion" do presente desafio, ou lista-rede-especialistas-ia.

### Avaliação ###

O score do participante será calculado através da métrica F1-score, calculada sobre os rótulos submetidos por ele. O vencedor do desafio será aquele que obtiver o maior score entre todos. É possível fazer diversas submissões.

Para mais informações sobre essa métrica, consulte:<br>
[https://en.wikipedia.org/wiki/F-score](https://en.wikipedia.org/wiki/F-score)<br>
[https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)

### Reprodutibilidade ###

O código desenvolvido deve oferecer reprodutibilidade dos resultados obtidos no leaderboard.

Portanto, caso uma solução utilize rotinas com aleatoriedade, estas deverão implementar semente(s) aleatória(s) fixa(s).

Uma boa submissão deve ter seu código correspondente versionado pelo participante. Este código poderá ser auditado ao final do desafio, caso a submissão se classifique entre as três primeiras.

Se não for obtida reprodutibilidade posterior de uma submissão, ela será descartada na avaliação final.

### Dados ###

Serão disponibilizados dois conjuntos de dados para os participantes. Um deles conterá perguntas de diferentes chatbots do Serpro, rotulados, para uso em treinamento e testes de classificadores. O segundo conterá perguntas sem rotulação, para serem classificadas e submetidas a esta página, para cálculo do score.

É vetado o uso destes dados fora do presente desafio.

Em caso de dúvidas sobre como os dados de treino/testes devem ser carregados e como os dados classificados devem ser submetidos, consulte nosso notebook de baseline em [https://www.kaggle.com/c/desafio-ia-2020-pln-chatbots/notebooks](https://www.kaggle.com/c/desafio-ia-2020-pln-chatbots/notebooks)

### Rules ###

#### Uma conta por participante ####

Você não pode se inscrever no Kaggle de várias contas e, portanto, não pode enviar de várias contas.

#### Limites de equipe ####

O tamanho máximo de equipe é de 3 membros, equipes podem ter mudanças somente nas primeiras 48 hs. Por exemplo, união de 2 ou mais times é permitida apenas nas primeiras 48 hs.

#### Limites de submissão ####

Você pode enviar no máximo 10 resultados por dia.

Você pode selecionar até 2 submissões finais para o julgamento.

#### Reprodutibilidade ####

O código desenvolvido deve oferecer reprodutibilidade dos resultados obtidos no leaderboard.

Portanto, caso uma solução utilize rotinas com aleatoriedade, estas deverão implementar semente(s) aleatória(s) fixa(s).

Uma boa submissão deve ter seu código correspondente versionado pelo participante. Este código poderá ser auditado ao final do desafio, caso a submissão se classifique entre as três primeiras.

Se não for obtida reprodutibilidade posterior de uma submissão, ela será descartada na avaliação final.

#### Regulamento ####

Leia com cuidado o regulamento do desafio, para não usar ferramentas, práticas ou serviços não permitidos: [https://drive.google.com/file/d/19a6MOBvM-kf2Id5o4CuScveRICZKzDrU/view](https://drive.google.com/file/d/19a6MOBvM-kf2Id5o4CuScveRICZKzDrU/view)

#### Propósito ####

Esta é uma competição divertida que visa ajudar você a começar no aprendizado de máquina. Embora o conjunto de dados esteja publicamente disponível na Internet, procurar respostas prontas acaba com todo o propósito. Ou seja, não faça isso. :D

Não trapaceie!

Aplique-se!

Divirta-se!

### Perguntas mais frequentes ###

[Acesse](https://sites.google.com/serpro.gov.br/desafio-ia-2020-faq/in%C3%ADcio)

