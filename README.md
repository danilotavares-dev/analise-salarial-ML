# Análise Salarial com Machine Learning

Um projeto completo de **Ciência de Dados e Machine Learning** desenvolvido para prever **faixas salariais** com base em características profissionais e demográficas, como cargo, nível de experiência e formação acadêmica.

O sistema inclui **três camadas principais**:
- Treinamento do modelo de aprendizado de máquina (Jupyter Notebook)
- API em Python para servir o modelo
- Interface interativa desenvolvida com Streamlit

---

## Objetivo do Projeto
O objetivo é explorar um conjunto de dados salariais e construir um modelo preditivo capaz de estimar o salário de um profissional com base em variáveis como:
- Cargo ou área de atuação  
- Tempo de experiência  
- Nível de escolaridade  
- Localização  

Esse tipo de análise é útil para **recursos humanos**, **consultorias de carreira** e **análises de mercado de trabalho**.

---

## Tecnologias Utilizadas
- **Python 3.10+**
- **Pandas**, **NumPy** — manipulação e análise de dados  
- **Scikit-learn** — criação e avaliação do modelo de Machine Learning  
- **Matplotlib** — visualização dos dados  
- **Streamlit** — interface interativa para uso do modelo  
- **Pipenv** — gerenciamento de dependências  
- **Pickle** — serialização do modelo treinado  

---

## Etapas do Projeto

1. **Análise Exploratória dos Dados (EDA)**
   - Limpeza, padronização e tratamento de valores ausentes  
   - Identificação de correlações entre variáveis  
   - Visualização de distribuições e tendências salariais  

2. **Construção do Modelo**
   - Codificação de variáveis categóricas  
   - Normalização dos dados  
   - Testes com diferentes algoritmos de regressão  
   - Avaliação com métricas como R² e RMSE  

3. **API do Modelo**
   - Implementação em Python (`api_modelo_salario.py`)  
   - Endpoint para envio de dados e retorno da previsão de salário  

4. **Aplicação Streamlit**
   - Interface simples e intuitiva para inserir informações e visualizar o salário estimado  
   - Permite testar o modelo em tempo real  

---

## Como Executar Localmente

### 🔧 Pré-requisitos
- Python 3.10+
- Pipenv instalado

### Passos
```bash
# 1. Clonar o repositório
git clone https://github.com/danilotavares/analise-salarial-ml.git
cd analise-salarial-ml

# 2. Instalar dependências
pipenv install

# 3. Ativar o ambiente virtual
pipenv shell

# 4. Rodar o app Streamlit
streamlit run app_streamlit_salario.py
