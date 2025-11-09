# Projeto: Predição de Doença Cardiovascular com Regressão Logística

Este projeto consiste na construção de um modelo de classificação para prever a presença de doença cardiovascular com base em variáveis clínicas e comportamentais, utilizando Regressão Logística.

## 📊 Objetivo

Criar um modelo preditivo que ajude a identificar indivíduos com maior risco de desenvolver doenças cardiovasculares, com base em dados como idade, colesterol, IMC, hábito de fumar, entre outros.

## 🧪 Etapas Realizadas

1. **Exploração inicial dos dados**
   - Verificação de nulos, tipos e distribuição.
2. **Visualização**
   - Gráficos de boxplot e histogramas para entender padrões por classe-alvo.
3. **Correlação**
   - Matriz de correlação apontando variáveis com maior influência.
4. **Pré-processamento**
   - Separação em treino e teste
   - Verificação de balanceamento
   - Padronização se necessário
5. **Modelagem**
   - Treinamento com regressão logística
   - Avaliação com métricas: accuracy, precision, recall, F1
6. **Validação**
   - Métricas no conjunto de teste
   - Curva ROC-AUC
7. **Conclusão**
   - O modelo apresentou performance razoável (AUC = 0.70), podendo ser ponto de partida para modelos mais robustos no futuro.

## 📈 Principais Resultados

- **Acurácia (teste):** 63.9%
- **F1-score (teste):** 62.7%
- **AUC-ROC:** 0.70
- **Principais variáveis correlacionadas:** Colesterol, Idade, Consumo de Álcool, Peso

## 🛠️ Tecnologias Utilizadas

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

## 📁 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```
2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate   # Windows
```
3. Instale as dependências:
```bash
pip install -r requirements.txt
```
4. Execute o notebook:
```bash
jupyter notebook
```

## 🧠 Conclusão

A regressão logística foi eficiente para iniciar a análise preditiva com bons resultados de classificação binária. O projeto também demonstrou domínio em todas as etapas de pré-processamento, modelagem e avaliação.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.