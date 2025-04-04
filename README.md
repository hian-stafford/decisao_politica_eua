# Análise de Votos do Congresso com Redes Neurais em Keras

## Visão Geral

Este projeto utiliza **redes neurais artificiais** para prever o partido político de congressistas dos Estados Unidos com base em seus votos em diferentes pautas legislativas. Para isso, utilizamos **Keras** para construir um modelo de deep learning e o **Scikit-Learn** para realizar a avaliação do modelo através de **validação cruzada**.

Os dados são baseados nos votos de 1984, um período em que a polarização política não era tão acentuada como nos dias atuais. Ainda assim, o modelo consegue obter uma acurácia superior a **94%**, demonstrando que os padrões de votação são indicadores fortes da filiação partidária.

## Motivação e Aplicações

A capacidade de prever a filiação política com base nos padrões de votação é útil para diversas áreas, como:

- **Ciência Política:** Análise de tendências partidárias e comportamento legislativo.
- **Análise de Dados:** Demonstração de como dados categóricos podem ser modelados para previsões eficazes.
- **Aprendizado de Máquina:** Aplicação prática de redes neurais em problemas reais de classificação binária.

## Tecnologias Utilizadas

- **Python 3**
- **Pandas** para manipulação de dados
- **TensorFlow/Keras** para construção da rede neural
- **Scikit-Learn** para validação cruzada

## Estrutura do Projeto

1. **Pré-processamento dos dados**
   - Carregamento e limpeza dos dados
   - Substituição de valores categóricos por valores numéricos
   - Remoção de valores ausentes
2. **Criação do Modelo**
   - Implementação de uma rede neural com duas camadas ocultas usando Keras
   - Utilização da função de ativação ReLU nas camadas ocultas e Sigmoid na camada de saída
   - Uso da função de perda **binary\_crossentropy** e do otimizador **Adam**
3. **Treinamento e Avaliação**
   - Utilização de validação cruzada com 10 folds para uma avaliação robusta
   - Cálculo da acurácia média do modelo

## Resultados

O modelo alcançou uma acurácia média de **94,38%**, demonstrando sua capacidade de prever com alta precisão a filiação partidária com base nos votos em diferentes pautas legislativas.

## Considerações Finais

Este projeto demonstrou como **redes neurais** podem ser aplicadas na análise política e como a integração com o **Scikit-Learn** permite uma avaliação mais robusta do desempenho do modelo. Ele pode ser expandido para incluir:

- Testes com diferentes arquiteturas de rede.
- Implementação de técnicas de balanceamento de dados.
- Uso de modelos alternativos como SVM e Random Forest para comparação.

Se você deseja entender melhor como redes neurais podem ser aplicadas em problemas reais de **classificação binária**, este projeto é um excelente ponto de partida!

---

### **Autor**

Desenvolvido por [Hian Stafford], com foco na aplicação de machine learning para análise política.
