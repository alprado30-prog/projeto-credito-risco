# Projeto Avaliativo Módulo 1 - Pipeline de Risco de Crédito
Curso: Carreira Tech - Trilha IA - Fundamentos de Programação, Dados e Machine Learning - S25134
Instituição: SCTEC / SENAI
Aluna: EDNA APARECIDA LAVANDOSKI DO PRADO

Objetivo: Prever risco de inadimplência (loan_status)

Fase 1 - EDA: Análise exploratória - idades inválidas e desbalanceamento
Fase 2 - Preparação: Limpeza de nulos e idades <18 e >80 - Garbage In Garbage Out
Fase 3 - Engenharia de Recursos: renda_por_idade, credito_por_renda, risco_juros_percent
Fase 4 - Pipeline seguro com StandardScaler e OneHotEncoder sem vazamento de dados
Fase 5 - Modelagem com KNN, Árvore de Decisão (max_depth=6, min_samples_leaf=10) e RandomForest - controle de Overfitting
Fase 6 - Validação com 90,41% de acurácia e veredito de negócios para evitar prejuízos

Arquivos:
- pipeline_credito.ipynb
- conjunto_de_dados_de_risco_de_crédito.csv
- pipeline_credito.pkl é gerado ao rodar o notebook (excede 25MB do GitHub)
