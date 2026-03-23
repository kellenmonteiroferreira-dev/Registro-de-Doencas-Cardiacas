## Registro-de-Doencas-Cardiacas
## Análise de Dados de Doença Cardíaca
## Análise Preditiva de Doença Cardíaca

## Introdução
Este projeto tem como objetivo prever a presença de doença cardíaca com base em dados de saúde. Utilizamos um modelo de Regressão Logística para classificar pacientes, apoiando decisões médicas.

## Tecnologias e Linguagens
- Linguagem: Python
- Bibliotecas: pandas, numpy, scikit-learn, matplotlib
- Ambiente: Google Colab

## Metodologia
1. Importação e limpeza dos dados: foram carregadas variáveis como idade, sexo, pressão e colesterol.
2. Análise Exploratória: verificação de distribuições e correlações entre as variáveis.
3. Divisão dos dados: separamos 80% para treino e 20% para teste.
4. Modelo: treinamos uma Regressão Logística usando o scikit-learn.
5. Avaliação: medimos acurácia (85%), precisão, recall e calculamos a curva de precisão-recall (AUC-PR).

## Resultados Obtidos
O modelo obteve uma acurácia de 85%, com uma AUC-PR de 0,95, indicando boa capacidade de identificar os casos positivos. A análise exploratória também mostrou variáveis-chave, como idade e pressão, que influenciam no risco.

## Conclusão
Este projeto demonstra o uso de Regressão Logística em Python para classificação, oferecendo um modelo robusto para apoio à decisão em saúde. O código está disponível no repositório e pode ser adaptado para outros cenários.

## Como Executar
1. Clonar o repositorio.
2. Instalar as dependências (`pandas`, `numpy`, `scikit-learn`, `matplotlib`).
3. Executar no Google Colab ou ambiente local com Jupyter.



## Autor
Kellen Ferreira.
