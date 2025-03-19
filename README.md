# Predição de Volatilidade das Ações da NVIDIA com RNN

Este projeto utiliza um modelo de Redes Neurais Recorrentes (RNN) para prever o preço de fechamento das ações da NVIDIA, com base em um conjunto de dados de série temporal do Kaggle (2014-2024). O modelo é implementado com TensorFlow/Keras.

O dataset é carregado e processado para remover valores ausentes e organizar os dados em ordem cronológica.

A arquitetura da RNN conta com 50 neurônios na camada oculta e ativação ReLU, permitindo capturar relações temporais entre os preços das ações. Para avaliação da performance, é utilizada a métrica Mean Squared Error (MSE), adequada para problemas de regressão financeira.