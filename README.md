📊 Projeto Walmart - Previsão de Vendas Semanais
📚 Coleta de Dados
Os dados utilizados neste projeto foram obtidos do Kaggle, no conjunto "Walmart Sales Forecasting".
Arquivos utilizados:

features.csv: informações de temperatura, preço de combustível, feriados, CPI e desemprego;

stores.csv: tipo e tamanho das lojas Walmart;

train.csv: dados históricos de vendas semanais por loja e departamento;

test.csv: conjunto para validação futura do modelo preditivo.

O carregamento dos dados foi realizado com a biblioteca pandas em Python, e o ambiente de desenvolvimento utilizado foi o Jupyter Notebook.
As bibliotecas matplotlib e seaborn foram utilizadas para visualização gráfica dos dados.

🛠️ Modelagem
As etapas realizadas até o momento incluem:

Carregamento e validação dos dados;

Análise exploratória para identificar padrões, tendências e sazonalidade nas vendas;

Verificação do impacto de variáveis externas como feriados, temperatura e taxa de desemprego.

Próximas etapas planejadas:

Aplicação de PCA (Análise de Componentes Principais) para redução de dimensionalidade;

Uso de K-Means para segmentação de lojas baseadas em características de vendas;

Construção de modelos de Regressão para previsão de vendas semanais;

Aplicação de técnicas de combinação de modelos para otimizar a performance preditiva.

📈 Conclusões Iniciais
A variável "feriados" mostrou forte influência nas vendas semanais;

O aumento no preço dos combustíveis parece impactar negativamente as vendas em algumas lojas;

Existem diferenças de comportamento entre lojas de tamanhos e tipos distintos;

As séries temporais indicam padrões sazonais fortes, o que poderá ser explorado para melhorar a previsão futura.

