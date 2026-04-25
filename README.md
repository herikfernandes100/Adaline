# 🧠 Adaline em Python

Implementação de um **Adaline (Adaptive Linear Neuron)** desenvolvido em Python, com foco em aprendizado supervisionado, ajuste de pesos utilizando a **regra LMS** e análise da evolução do erro.

Projeto desenvolvido por **Hérik Fernandes e Rafael Gonçalves**.

---

## 🚀 Funcionalidades

- 🧠 Implementação do algoritmo Adaline  
- ⚖️ Atualização de pesos com regra LMS (Widrow-Hoff)  
- 🔁 Treinamento por épocas  
- 📉 Cálculo do erro médio quadrático (EQM)  
- 📊 Plotagem do gráfico de erro  
- 💾 Salvamento automático dos pesos em `.json`  
- 📂 Carregamento de pesos salvos  
- 🔍 Previsão de novos dados  
- 📈 Cálculo de acurácia  

---

## 🛠️ Tecnologias utilizadas

- 🐍 Python  
- 📊 Matplotlib  
- 📁 JSON  
- 🎲 Random  

---

## 📂 Estrutura do Projeto

- **Adaline** → Classe principal do modelo  
- **pesos** → Lista de pesos do modelo  
- **treinar()** → Método de treinamento  
- **prever()** → Método de previsão  
- **plotar_grafico()** → Visualização do erro  
- **salvar_pesos()** → Persistência dos pesos  
- **carregar_pesos()** → Leitura dos pesos salvos  

---

## 🧠 Como funciona o Adaline

O modelo:

- Recebe entradas  
- Calcula a soma ponderada (u)  
- Calcula o erro:  
