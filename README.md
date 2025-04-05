# 🧠 ADALINE - Adaptive Linear Neuron

Este repositório contém a implementação do **ADALINE**, um modelo de rede neural artificial para classificação binária, desenvolvido como parte da disciplina de **Redes Neurais Artificiais**.

## 🔬 Sobre o ADALINE

O **ADALINE** é um algoritmo de aprendizado supervisionado proposto por Bernard Widrow e Marcian Hoff na década de 1960. Diferente do Perceptron, que utiliza uma função de ativação degrau, o ADALINE trabalha com um modelo linear baseado no erro mínimo quadrático. O ajuste dos pesos é realizado por meio da **Regra da Aprendizagem Delta**, que minimiza a diferença entre a saída desejada e a real.

## 🎯 Objetivo da Atividade

Nesta atividade, o ADALINE foi treinado para classificar amostras em duas categorias distintas, utilizando diferentes configurações de taxa de aprendizado e critério de parada. Foram realizados experimentos com:
- Aprendizado **batch** (ajuste dos pesos com base em todas as amostras de uma vez);
- Aprendizado **online** (ajuste dos pesos a cada amostra processada);
- Diferentes taxas de aprendizado (𝜂) e critérios de parada para observar seu impacto na convergência do modelo.

## 🛠 Tecnologias Utilizadas

- Python 3.12.8
- NumPy 2.2.4
- Matplotlib 3.10.1
- Pandas 2.2.3

## 📊 Visualização dos Dados

O código gera gráficos que mostram:
- A evolução do erro ao longo das épocas;
- A distribuição das amostras de treinamento e teste;
- A fronteira de decisão aprendida pelo ADALINE.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
