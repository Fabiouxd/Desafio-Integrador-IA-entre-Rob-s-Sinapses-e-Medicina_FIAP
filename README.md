📋 Sobre o Projeto
O CardioIA é um ecossistema de Inteligência Artificial voltado para a cardiologia moderna. Nesta Fase 2, o foco foi a transição de dados brutos para diagnósticos assistidos, utilizando processamento de linguagem natural (NLP), modelos clássicos de Machine Learning para triagem de risco e Redes Neurais Profundas (Deep Learning) para análise de sinais vitais.

O projeto demonstra como algoritmos podem atuar como "estetoscópios digitais", auxiliando médicos na priorização de atendimentos e na precisão diagnóstica.

🚀 Tecnologias Utilizadas
Linguagem: Python 

NLP & Regras: Expressões Regulares e Ontologias em CSV.

Machine Learning: Scikit-Learn (TF-IDF, Logistic Regression).

Deep Learning: TensorFlow / Keras (Multilayer Perceptron - MLP).

Manipulação de Dados: Pandas, NumPy, KaggleHub.

Visualização: Matplotlib, Seaborn.

🛠️ Estrutura da Solução
1. Extração de Sintomas e Ontologia (NLP)
Implementamos um módulo de extração que utiliza uma base de conhecimento (ontologia) para correlacionar sintomas relatados por pacientes a possíveis diagnósticos.

Dataset: 10 relatos médicos simulados em .txt.

Mapeamento: Mapa de conhecimento com mais de 30 correlações entre sintomas e doenças cardíacas.

2. Classificador de Risco (Machine Learning)
Desenvolvemos um classificador binário para triagem clínica automatizada.

Método: Vetorização de texto via TF-IDF (Term Frequency-Inverse Document Frequency).

Modelo: Regressão Logística para classificação entre Alto Risco e Baixo Risco.

Objetivo: Auxiliar na priorização de filas de emergência com base na gravidade relatada.

3. Diagnóstico Visual com Redes Neurais (Ir Além 2)
Utilizamos o dataset oficial MIT-BIH Heartbeat para treinar uma Rede Neural Artificial (MLP).

Dados: Sinais de ECG reais (Kaggle).

Arquitetura: MLP com camadas de normalização (BatchNormalization) e regularização (Dropout) para evitar overfitting.

Performance: O modelo alcança alta acurácia na distinção entre batimentos normais e arritmias cardíacas.

📂 Como Executar o Projeto
Clone o repositório:

Bash
git clone [LINK-DO-SEU-REPOSITORIO]
Instale as dependências:

Bash
pip install pandas numpy scikit-learn tensorflow matplotlib kagglehub
Execute os Notebooks:

Abra o arquivo .ipynb no Google Colab ou Jupyter Notebook.

O download do dataset do Kaggle é feito automaticamente via script.

🎥 Demonstração e Resultados
Confira o vídeo com a explicação técnica e demonstração das ferramentas funcionando:

🔗 [Link do Vídeo no YouTube (Não Listado)]

Nota: Este projeto faz parte do currículo de Inteligência Artificial da FIAP (Fase 2 - PBL).
