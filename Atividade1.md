# Atividade 1 - Bootcamp Avanti - Machine Learning
### Aluna: Karen Ribeiro

#### 1. Explique, com suas palavras, o que é machine learning?

Machine Learning, também conhecido como Aprendizado de Máquina, é um campo da Inteligência Artificial que se dedica ao desenvolvimento de sistemas capazes de aprender com dados, utilizando algoritmos e modelos estatísticos. Esses sistemas são treinados para aprimorar seu desempenho ao identificar padrões e correlações a partir dos dados que analisam. Como resultado, eles conseguem prever resultados com maior precisão baseando-se em um conjunto específico de dados de entrada.

Inicialmente, dados são fornecidos a um algoritmo de Machine Learning, que realiza o treinamento do modelo para aprender a identificar padrões nesses dados. Depois disso, o modelo de Machine Learning pode ser testado, avaliado, otimizado e colocado em produção, conforme o objetivo da aplicação.

Alguns exemplos são: Previsão e Análise, 
Reconhecimento de padrões e Otimização de processos

#### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

 - Treinamento: O conjunto de treinamento é utilizado para ajustar os parâmetros durante a criação do modelo, permitindo que ele aprenda a relação entre as variáveis de entrada e saída. Geralmente, esses dados representam cerca de 70% do total disponível.
 - Teste: O conjunto de teste é utilizado para avaliar o desempenho do modelo em dados não vistos durante o treinamento. É com esse conjunto que se verifica se o modelo realmente aprendeu algo a partir dos dados e o utilizamos como métrica para sua avaliação. Normalmente, o conjunto de teste representa cerca de 15% do total de dados disponíveis.
 - Validação: O conjunto de validação é utilizado para avaliar o desempenho do modelo durante o treinamento. Ele verifica quantos elementos do conjunto de teste foram rotulados corretamente, permitindo ajustes no modelo para melhorar seu desempenho. Os outros 15% dos dados estão nesse conjunto.


#### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Existem algumas estratégias de tratamento em um contexto de dados faltantes em um conjunto de dados, que podem ser causados por fatores como limitação da empresa, erro humano no preenchimento, perdas, etc. Cada uma dessas abordagens tem suas vantagens e deve ser escolhida com base na natureza dos dados, na quantidade de dados faltantes e nos requisitos específicos da análise ou modelo em questão.

- Imputação de Média/Mediana/Moda: Utilização de métodos estatísticos como média, mediana ou moda para preencher valores faltantes em dados numéricos. Isso ajuda a manter a integridade dos dados e pode ser aplicado quando a distribuição dos dados é aproximadamente normal.

- Imputação por Regressão: Criação de um modelo de regressão com base nas variáveis completas do conjunto de dados para prever e preencher os valores faltantes. Esta abordagem é útil quando existe correlação entre as variáveis e pode melhorar a precisão da imputação.

- Exclusão de Dados: Remoção dos registros que possuem dados faltantes. Essa estratégia é apropriada quando a quantidade de dados faltantes é pequena em relação ao tamanho total do conjunto de dados e a exclusão não compromete a validade ou representatividade dos resultados.

#### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

A matriz de confusão, também conhecida como matriz de erro, é uma tabela que compara o desempenho de um modelo de previsão ao confrontar os valores previstos com os valores reais da variável de destino. Ela é estruturada com colunas representando as previsões do modelo e linhas representando as observações reais. Os elementos da matriz incluem:

- Verdadeiros Positivos (VP): Casos em que o modelo previu corretamente a classe positiva.
- Falsos Positivos (FP): Casos em que o modelo previu incorretamente a classe positiva (em realidade negativa).
- Verdadeiros Negativos (VN): Casos em que o modelo previu corretamente a classe negativa.
- Falsos Negativos (FN): Casos em que o modelo previu incorretamente a classe negativa (em realidade positiva).

A matriz de confusão é utilizada na avaliação do desempenho de modelos preditivos principalmente para:

- Avaliação de Modelos de Classificação: Fornecer uma visão detalhada da qualidade das previsões do modelo, utilizando um limiar de decisão que transforma uma faixa de probabilidades em categorias previstas.
- Cálculo de Métricas: Calcular métricas que quantificam o desempenho do modelo, como especificidade, precisão, acurácia, sensibilidade (recall), entre outras.


#### 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?

A administração é uma grande área dentro das ciências sociais aplicadas, abrangendo diversas subáreas como Finanças, Operações, Recursos Humanos, entre outras. Eu acredito fortemente que a Administração possui vastas oportunidades para aplicações de Machine Learning, por exemplo:
- Finanças: Em detecção de fraudes, análise de crédito, previsão de mercado financeiro, investimentos automatizados, etc.
- Varejo: Previsão de demanda, otimização de preços, análise de sentimentos de clientes, etc.
- Segmentação de Mercado e Personalização: Segmentar clientes com base em padrões de comportamento de compra e outras variáveis, criar campanhas de marketing mais direcionadas e personalizadas.
- Gestão de Recursos Humanos: Prever a rotatividade de funcionários, otimizar processos de recrutamento e seleção.
- Análise de Desempenho e Produtividade: Utilizar dados operacionais para identificar áreas de baixa eficiência ou gargalos, sugerir melhorias nos processos internos.




----------

##### Fontes:
- ##### [Oracle](https://www.oracle.com/br/artificial-intelligence/machine-learning/what-is-machine-learning/)
- ##### [AWS Amazon](https://aws.amazon.com/pt/what-is/machine-learning/)
- ##### [Dataside](https://www.dataside.com.br/dataside-community/a-i-e-machine-learning/pipeline-de-machine-learning)
- ##### [DataEx](https://www.dataex.com.br/machine-learning-um-guia-atualizado/)
- ##### [Academia Tech](https://academiatech.blog.br/matriz-de-confusao/)
- ##### [SAP](https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/18850a0e13944f53aa8a8b7c094ea29e/5bcbbd16881f407eb706c0491725c5d9.html?version=2024.12)
- ##### [Awari](https://awari.com.br/tratamento-de-dados-ausentes-o-tratamento-de-dados-ausentes/)

