# Desafio IA 2020 - Etapa Modelos Preditivos #
### Organized by: Rede de Especialistas ###
Starts on: Out 13, 2020 12:00:00 PM
Ends on: Out 26, 2020 06:00:00 PM 

[Kaggle Challenge Page](https://www.kaggle.com/c/desafioiamp2020)

## Challenge Overview ##

### Descrição do desafio ###

O objetivo deste desafio é realizar a predição de valores de diárias para se hospedar no Rio de Janeiro usando-se dados disponibilizados a partir do site Airbnb. Para isso serão disponibilizados os dados com as características do imóvel a alugar.

### Sobre o conjunto de dados ###

O conjunto de dados deste desafio foi produzido a partir da base de 2019. Os dados foram coletados, sob Creative Commons 1.0, a partir de: [http://insideairbnb.com/get-the-data.html](http://insideairbnb.com/get-the-data.html).

#### Colunas disponíveis ####

* id: discreto
* host_name: apelido do proprietário
* amenities: texto com lista de comodidades
* zipcode: CEP
* latitude: discreto
* longitude: discreto
* price: valor da diária por pessoa
* accommodates: número de pessoas que podem se acomodar, segundo o proprietário
* bedrooms: número de quartos
* cleaning_fee: taxa de limpeza
* beds: número de camas
* bathrooms: número de banheiros
* security_deposit: depósito do seguro
* guests_included: quantos convidados são aceitos
* calculated_ host _listings _count: número atual de anúncios vigentes do proprietário
* host_ is_ superhost: categórico
* host_ response_ time: categórico
* minimum_nights: número mínimo de diárias
* extra_people: diária adicional por pessoa
* host_ identity_ verified: categórico
* maximum_nights: número máximo de diárias
* bed_type: categórico
* cancellation_policy: categórico
* property_ type: categórico
* numberofreviews: número total de reviews de hóspedes, dado histórico
* instant_bookable: categórico
* host_ response_ rate: taxa (em percentual)
* review_ scores_ location: discreto (nota de 0 a 10)
* review_ scores_ cleanliness: discreto (nota de 0 a 10)
* review_ scores_ accuracy: discreto (nota de 0 a 10)
* review_ scores_ checkin: discreto (nota de 0 a 10)
* review_ scores_ communication: discreto (nota de 0 a 10)
* neighbourhood: bairro
* review_ scores_ value: discreto (nota de 0 a 10)
* room_type: categórico

### Objetivo ###

É seu trabalho prever o valor do preço faltante. Para cada registro do conjunto de testes, você deve prever um valor numérico (real positivo) para a variável (preço).

### Métrica ###

Sua pontuação será calculada a partir da raiz do erro quadrático médio (do inglês Root Mean Squared Error - RMSE) sobre os dados enviados.

O desvio da raiz quadrada média ou da raiz quadrada média é uma medida freqüentemente usada das diferenças entre os valores preditos por um modelo ou um estimador e os valores observados.

Maiores informações sobre RMSE:

[https://pt.wikipedia.org/wiki/Erro_quadr%C3%A1tico_m%C3%A9dio](https://pt.wikipedia.org/wiki/Erro_quadr%C3%A1tico_m%C3%A9dio)
[https://en.wikipedia.org/wiki/Root-mean-square_deviation](https://en.wikipedia.org/wiki/Root-mean-square_deviation)

### Formato do arquivo de submissão ###

Você deve enviar um arquivo CSV com exatamente a quantidade de registros do teste. Seu envio mostrará um erro se você tiver linhas ou colunas extras.

O arquivo deve ter exatamente 3294 registros (3293 predições e 1 cabeçalho) e 2 colunas:

* id: id do arquivo de teste
* price: valor da diária da predição

### Rules ###

#### Uma conta por participante ####

Você não pode se inscrever no Kaggle de várias contas e, portanto, não pode enviar de várias contas.

#### Limites de equipe ####

O tamanho máximo de equipe é de 3 membros, equipes podem ter mudanças somente nas primeiras 48 hs. Por exemplo, união de 2 ou mais times é permitida apenas nas primeiras 48 hs.

#### Limites de submissão ####

Você pode enviar no máximo 10 resultados por dia.
Você pode selecionar até 2 submissões finais para o julgamento.

#### Propósito ####
Esta é uma competição divertida que visa ajudar você a começar no aprendizado de máquina. Embora o conjunto de dados esteja publicamente disponível na Internet, procurar respostas prontas acaba com todo o propósito. Ou seja, não faça isso. :D

Não trapaceie!
Aplique-se!
Divirta-se!

### Perguntas mais frequentes ###

[Acesse](https://sites.google.com/serpro.gov.br/desafio-ia-2020-faq/in%C3%ADcio)

