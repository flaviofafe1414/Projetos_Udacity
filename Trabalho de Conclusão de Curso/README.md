
# Nanodegree Engenheiro de Machine Learning
## Projeto: Proposta de projeto final e projeto final




Resumo: Visão Geral do Projeto
A diabetes está presente em cerca de 415 milhões de pessoas1, ocorrendo em duas variações: tipo 1, ocorrendo quando a produção de insulina no pâncreas é insuficiente, pois cargas hereditárias causam a destruição de suas próprias células pancreáticas, tendo  os portadores a necessidade da administração de insulina, com o intuito de manter sua qualidade de vida e aliviar os sintomas. Já Diabetes do tipo 2 é uma doença crônica que atinge grande parcela mundial, ela é caracterizada como uma falha do organismo em não metabolizar a glicose consumida, ocasionando um aumento do nível de açúcar no sangue, podendo afetar diretamente o sistema renal, cardíaco e neurológico. O uso de técnicas de aprendizado de máquina para a área de saúde tem tido um grande interesse por parte dos pesquisadores, usadas frequentemente para o controle de epidemias, auxilio a exames clínicos, monitoramento do estado de pacientes, dosagem de medicamentos e auxilio para o diagnóstico médico. Assim como em outras doenças, a falta de um diagnóstico correto e rápido pode ter graves consequências. Em 2010 Patil et al, descreveram uma abordagem para o diagnostico de diabetes do tipo 2, na qual foi combinado um algoritmo de treinamento,  k-médias com algoritmo C4.5. Neste contexto, o trabalho de conclusão de curso baseia-se em estudar uma base de dados fornecidos pela Kaggle, denominado como “Pima Indians Diabetes Database”, na qual foi realizado um estudo com três diferentes algoritmos de machine Learning (“Regressão Logística, Random Forest e Support Vector machine”) para criação de um modelo que possa avaliar a possibilidade de um pacientes receber o diagnóstico de diabetes em função de certos atributos.


Estudos mostram que metades dos pacientes diagnosticadas com diabetes não sabiam de suas condições2, adotando os efeitos da doença como rotinas de suas vidas, como exemplo: fadiga, cansaço, dor de cabeça, visão dupla, boca seca e entre outros.  Com o objetivo de auxiliar os profissionais da saúde, tem-se desenvolvido métodos de aprendizado de máquina para encontrar características de riscos, que eventualmente possam ser trabalhadas como medidas preventivas. Sendo assim, o Dataset foi retirado da base de dados da Kaggle, denominado como “Pima Indians Diabetes Database”. Se tratando da coluna “Outcome” na qual nos informa se a pessoa tem diabetes ou não, respectivamente como sendo 1 ou 0. Como podemos observar, é uma variável categórica, sendo propicio usar métodos de classificação, sendo os possíveis candidatos, Regressão Logística, Random Forest e Support Vector Machines. Nele encontramos os seguintes dados de entradas: “Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age”.Neste Dataset temos todas variáveis como numéricas e serão denominadas como “Features”, com exceção de apenas uma, “Outcome” que será nosso “Target”, classificado como 0 para não diabético e 1 para diabético. O conjunto de dados apresentam 768 entradas com 9 colunas, sendo 500 classificados como não diabéticos e 268 como diabéticos. Notamos que este dados não apresentam valores faltantes como “NA”, mas um atributo importante, como o índice de glicose, diversas vezes apresenta o valor 0, quase 50% do Dataset são faltantes, o que torna um incomodo, pois a diabetes depende do nível de açúcar no sangue, com isso, há a necessidade de realizar um tratamento prévio dos dados, por outro lado, podemos comparar a eficiência do modelo, antes e depois do devido tratamento de dados. Outro ponto a notar-se, o Dataset não apresenta balanceamento entre a variável “Target”, sendo mais um desafio para a etapa de pré-processamento. O primeiro passo da solução é a analise exploratória dos dados, podendo encontrar valores como: faltantes, outliers, média de valores, mediana e correlação de Pearson. Os objetivos desse trabalho são a comparação direta de um Dataset não tratado com um devidamente modificado e a criação de um modelo que seja capaz de prever o diagnostico de diabetes em função de certos atributos.

## Referências
1.	GLAUBER, H.; KARNIELI, E. Preventing Type 2 Diabetes Mellitus: A Call for Personalized Intervention. The Permanente Journa
2.	MURPHY, S. M. E.; CASTRO, H. K.; SYLVIA, M. Predictive modeling in practice: improving the participant identification process for care management programs using condition-specific cut points. Population health management. v.14, n.4, p. 205-2 



Autor: Flávio Pinto De Almeida Filho


```python

```
