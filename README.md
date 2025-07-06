# Análise da Evolução da Energia Renovável Global (2000-2023)
Este projeto realiza uma análise de dados sobre a produção de energia renovável (solar, eólica, hidrelétrica e outras não especificadas) em dez países ao longo do século XXI. O objetivo é investigar tendências de crescimento, o comportamento da diversificação da matriz energética e a viabilidade de se criar modelos preditivos com base em dados históricos.

**Hipóteses Investigadas**
O trabalho foi estruturado em torno de três hipóteses centrais:

1 - "A produção de energia solar e eólica aumentou de forma mais acelerada do que a hidrelétrica."

2 - "A diversificação da matriz energética está crescendo mais nos países desenvolvidos."

3 - "É possível prever as tendências de produção de energia renovável com base em dados históricos."

**Principais Descobertas**
A análise revelou insights complexos e, por vezes, contraintuitivos:

Crescimento vs. Anomalia nos Dados (Hipótese 1): A análise visual demonstrou um crescimento massivo e inegável da produção de energia solar e eólica por mais de 20 anos. No entanto, uma queda acentuada e anômala nos dados agregados após 2020 fez com que uma análise puramente matemática de ponta a ponta (ano 2000 vs. 2023) indicasse um resultado negativo. A hipótese, portanto, é parcialmente refutada, revelando uma história de crescimento expressivo interrompida por uma peculiaridade nos dados mais recentes.

O Mito da Diversificação (Hipótese 2): A hipótese de que países desenvolvidos diversificam mais sua matriz foi refutada. A análise, através de um Índice de Diversificação criado para o projeto, mostrou que países em desenvolvimento como China e Brasil possuem uma matriz energética renovável mais equilibrada do que nações desenvolvidas como Reino Unido e Canadá, que demonstram alta dependência de poucas fontes.

Viabilidade da Previsão (Hipótese 3): A hipótese foi validada. Um modelo de Regressão Linear de baseline foi capaz de prever a produção total de energia com uma performance razoável (R² ≈ 0.51), confirmando que os dados históricos possuem valor preditivo e que a modelagem é uma ferramenta viável para estimar tendências futuras.

**Ferramentas Utilizadas**
- Python

- Pandas e NumPy para manipulação de dados.

- Matplotlib e Seaborn para visualização de dados.

- Scikit-learn para pré-processamento, modelagem e avaliação.

- GoogleColab como ambiente de desenvolvimento.
