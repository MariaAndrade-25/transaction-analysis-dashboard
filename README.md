# transaction-analysis-dashboard
💹 Dashboard de Performance e Auditoria de Transações
Este projeto apresenta uma análise visual detalhada de transações financeiras, focando em identificar gargalos operacionais e taxas de erro. O processo envolveu desde o tratamento de dados no Excel até a modelagem avançada no Power BI.

🛠️ Stack Tecnológica
Excel: Limpeza inicial e organização dos dados brutos.

Power BI: Modelagem de dados e criação de visualizações interativas.

DAX (Data Analysis Expressions): Criação de medidas calculadas e colunas inteligentes para limpeza e análise.

📊 Insights do Dashboard
Através das visualizações criadas, foi possível identificar:

Taxa de Falha de 51%: Um indicador crítico que exige revisão nos processos de sistema e humanos.

Tempo Médio de Processamento (126,6s): Com destaque para o erro de Timeout, que eleva a média para 240 segundos, representando o maior gargalo operacional.

Distribuição de Erros: Erros de sistema e humanos possuem volume idêntico (11 ocorrências cada), sugerindo a necessidade de treinamento e melhoria na infraestrutura.

🧠 Lógica DAX Aplicada
Neste projeto, utilizei DAX para criar métricas personalizadas, como:

Cálculo de Taxa de Falha % dinâmica.

Média de Tempo de Processamento filtrada por tipo de erro.

Limpeza de strings e tratamento de valores nulos diretamente no modelo.


