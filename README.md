# general
a. Como foi a definição da sua estratégia de modelagem?
O primeiro passo foi fazer a importação de bibliotecas e analisar os dados contidos nela. Feita essa análise o foco foi fazer a limpeza e pré processamento, bem como entender como cada uma das variáveis se relacionavam com o preço, o tipo de quarto e avaliações.

b. Como foi definida a função de custo utilizada?
A função de custo definida foi preço uma vez que haviam várias variáveis cujo tipo (int ou float) facilitavam a manipulação dos dados e aplicação de fórmulas. 

c. Qual foi o critério utilizado na seleção do modelo final?
Infelizmente, não consegui fazer um novo carregamento dos dados por motivos de limitação de ram no meu google colab, mas os modelos que acreditam que trariam melhor resultado seriam XGBoost e/ou SVM por estar tratando de dados estruturados e são as duas técnicas que melhor performam nesses casos. Não vejo necessidade de aplicação de redes neurais nessa situação.
d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este
método?
Utilizaria MSE (mean squared error) e R2 Score para comparação e validação dos dados.
e. Quais evidências você possui de que seu modelo é suficientemente bom?
Acredito qure alcançaria uma acurácia elevada com esses modelos

