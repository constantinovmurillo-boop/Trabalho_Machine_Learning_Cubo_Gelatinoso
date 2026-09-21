<img width="974" height="134" alt="651004942-0a53a0bf-93ba-4ff5-a853-cf0914d6eb95" src="https://github.com/user-attachments/assets/ee4bb882-d65b-4155-a880-60abb77464b0" />

# Trabalho_Machine_Learning_Cubo_Gelatinoso
Trabalho de Aprendizado de Máquina - Cubo Gelatinoso

## Cabeçalho
<!--ts-->
**Aluno:** Murillo Constantinov

**RM:** 2610072

**Turma:** Turma 2026

**Disciplina:** Aprendizado de Máquina

**Docente:** professor Dr. Daniel R. Cassar

**Instituição:** Ilum - Escola de Ciência

**Local:** Campinas -  SP, Brasil

**Data:** 13/09/2026

## Contextualização
<!--ts-->
O Cubo Gelatinoso é a primeira entrega da disciplina de Aprendizado de Máquina da Ilum, Escola de Ciência. Essa tarefa tem o objetivo de gerar um primeiro contado entre os estudantes e os estudos de Aprendizado de Máquina de forma independente, visando o tratamento, análise e manipulação de dados; instanciação, treino, teste e avaliação de modelos k-NN; e a alteração de diversos parâmetros e melhora dos modelos.

## Métodologia
<!--ts-->
A metodologia envolveu baixar o banco de dados adaptando-o para ser trabalhado, em seguida ele foi estudado, com análises exploratórias e estatísticas; limpo para ser trabalhado e divididos em atributos e target, sendo transformados para as necessidades durante o projeto. Em seguida, os dados foram separados em treino e teste, os atributos foram normalizados. Foi feito e avaliado um modelo Baseline para se ter uma base de desempenho. Foi desenvolvido e avaliado um algoritmo k-NN inicial, que teve alterações e testes de diferentes hiperparâmetros; por fim, foi feito um algoritmo k-NN final, que possui o melhor conjunto de hiperparâmetros encontrado, que foi testado e avaliado. A última etapa do trabalho envolveu a comparação do modelo k-NN final encontrado no trabalho e o modelo Baseline desenvolvido inicialmente. Todos os processos envolveram também pesquisa, estudo e aplicação de conceitos de Aprendizado de Máquina.

### Bibliotecas utilizadas
<!--ts-->
Para organizar a realização do projeto, foram importadas as bibliotecas a seguir. A biblioteca "statistics" foi usada para fazer análise e cálculos estatísticos dos dados. A biblioteca "pandas" foi usada para a manipulação e visualização dos dados. A biblioteca "numpy" teve uso em momentos de análises estatísticas. As bibliotecas "matplotlib" e "seaborn" foram utilizadas para construções gráficas. Os objetos importadas da biblioteca "sklearn" foram usadas para diversos fins; portanto, tiveram suas funções explicados nas seções em que foram utilizados. 

### Conjunto de dados
<!--ts-->
Em seguida, os dados escolhidos para ser trabalhados foram do dataset "Heart Disease dataset", no qual cada linha é um paciente com indicadores clínicos e diferentes graus de doença cardíaca, indo de 0 (ausência) a 4. Esse dataset foi encontrado no repositório _UCI Machine Learning_, contendo dados de Cleveland, Hungria, Suíça e VA Long Beach; porém ao baixar os dados, eles são um arquivo ZIP que contém os dados de cada local separadamente; portanto, houve o uso de IA para juntar esses dados em um único arquivo CSV.

## Resultados
<!--ts-->
O resultado obtido com o projeto foi um algoritmo k-NN com alta acurácia e alto F1-score, representando um bom modelo final para as previsões; porém, vale lembrar que deve-se realizar melhorias para usos reais na área da saúde, pois é apenas um modelo e não considera diversos parâmetros que existem e interferem em casos do dia-a-dia.

## Conclusão
<!--ts-->
O trabalho desenvolvido gerou um algoritmo k-NN com alto índice de acertos de sua classificação. Esse melhor desempenho veio do uso de hiperparâmetros de 31 vizinhos mais próximos, peso uniforme para os dados e métrica de distância Manhattan.

O trabalho permitiu aprofundamento na manipulação e tratamento de dados e estudo estatísticos; separação de dados de treino e de teste; uso de modelos Baseline; desenvolvimento, aplicações e uso de modelos k-NN; classificação binária; estudo de métricas de desempenho; além de ter realizado papel fundamental no aprendizado de diversos conceitos da área de Aprendizado de Máquina, Estatística e Programação.

## Agradecimentos
<!--ts-->
Agradeço ao professor docente Dr. Daniel R. Cassar, por lecionar as aulas das matérias de Aprendizado de Máquina e Estatística na Ilum, Escola de Ciência. 
Agradecimentos à Ana Luiza de Lima Silva e à Gabriela Oliveira de Lima Cabral, que auxiliaram no entendimento de certos conceitos e compartilharam materiais sobre os conteúdos que permitiram a realização do projeto.

## Referências
<!--ts-->
[1] JANOSI, A.; STEINBRUNN, W.; PFISTERER, M.; DETRANO, R. Heart Disease [dataset]. Irvine: UCI Machine Learning Repository, 1989. DOI: https://doi.org/10.24432/C52P4X. Disponível em: https://archive.ics.uci.edu/dataset/45/heart+disease. Acesso em: 31 ago. 2026.

[2] CASSAR, Daniel R. ATP-203 1.1 - Tratamento de dados com pandas. 2026. Jupyter Notebook. Material didático não publicado

[3] CASSAR, Daniel R. ATP-203 2.1 - Aprendizado de máquina, k-NN e métricas. 2026. Jupyter Notebook. Material didático não publicado.

[4] CASSAR, Daniel R. ATP-203 2.2 - Divisão de dados em treino e teste. 2026. Jupyter Notebook. Material didático não publicado.

[5] FACELI, Katti; LORENA, Ana Carolina; GAMA, João; ALMEIDA, Tiago Agostinho; CARVALHO, André Carlos Ponce de Leon Ferreira de. Inteligência artificial: uma abordagem de aprendizado de máquina. 2. ed. Rio de Janeiro: LTC, 2021.

[6] SCIKIT-LEARN DEVELOPERS. DistanceMetric — scikit-learn 1.9.1 documentation. [S. l.]: scikit-learn, 2026. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.metrics.DistanceMetric.html. Acesso em: 4 set. 2026.

[7] PEDREGOSA, F. et al. scikit-learn: sklearn.metrics — accuracy_score, f1_score, roc_curve. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html. Acesso em: 4 set. 2026.

[8] HASTIE, Trevor; TIBSHIRANI, Robert; FRIEDMAN, Jerome. The elements of statistical learning: data mining, inference, and prediction. 2. ed. New York: Springer, 2009.

[9] HAN, Jiawei; KAMBER, Micheline; PEI, Jian. Data mining: concepts and techniques. 3. ed. Waltham: Morgan Kaufmann, 2012.

[10] GOOGLE. Curso intensivo de machine learning: classificação — ROC e AUC. Disponível em: https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc?hl=pt-br. Acesso em: 12 set. 2026.

## Docente responsável
<!--ts-->
| <img loading="lazy" src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub> [Prof. Dr. Daneiel Roberto Cassar](http://lattes.cnpq.br/1717397276752482) |
| :--: |

## Desenvolvedor
<!--ts-->
Murillo Constantinov, estudante do segundo semestre do bacharelado em Ciência e Tecnologia da Ilum escola de ciência.

<img width="966" height="95" alt="image" src="https://github.com/user-attachments/assets/f9825ded-4549-4691-a6e0-e261bfeb7aa1" />
