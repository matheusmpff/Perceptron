# Perceptron
Projeto desenvolvido em Python utilizando a biblioteca Scikit-learn para implementar e explorar o funcionamento do algoritmo Perceptron, um dos modelos fundamentais de aprendizado de máquina supervisionado.

A partir de um conjunto de dados sintético com duas classes, o projeto demonstra o treinamento do modelo, a classificação de pontos e a construção da fronteira de decisão que separa as classes. Também são exploradas métricas de avaliação, como acurácia e matriz de confusão, para analisar o desempenho do classificador.

Além disso, os dados e resultados obtidos durante o treinamento foram utilizados para desenvolver uma animação com Manim, ilustrando visualmente o processo de classificação pelo Perceptron e as mudanças na fronteira de decisão ao longo do aprendizado.

**Tecnologias utilizadas:** Python, Scikit-learn, NumPy, Matplotlib e Seaborn.

**Objetivo**: compreender, na prática, os fundamentos da classificação binária e do aprendizado de máquina por meio de experimentação e visualização dos resultados.

## Como executar o projeto

O Docker permite executar o projeto em um ambiente previamente configurado, sem precisar instalar manualmente as dependências do Python na máquina. O contêiner disponibiliza o JupyterLab para executar o notebook e visualizar os resultados.

**Pré-requisitos:** Docker e Docker Compose.

1. Clone o repositório:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd Perceptron
   ```

2. Inicie o ambiente:

   ```bash
   docker compose up --build
   ```

3. Acesse o JupyterLab

4. Abra o notebook `notebook/perceptron.ipynb` e execute as células.

Para encerrar o ambiente, execute:

```bash
docker compose down
```
