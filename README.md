# 🐱🐶 Treinamento de Redes Neurais com Transfer Learning

Este repositório contém o desenvolvimento completo de um modelo de Deep Learning para classificação de imagens de **gatos** e **cachorros** utilizando **Transfer Learning** com a arquitetura MobileNetV2.

O projeto foi desenvolvido como parte do bootcamp **BairesDev for AI Experts – DIO**, aplicando técnicas modernas de visão computacional e reutilização de redes pré-treinadas.

---

## 🚀 Tecnologias e Conceitos Utilizados
- TensorFlow e Keras  
- MobileNetV2 pré-treinada em ImageNet  
- Transfer Learning (camadas congeladas + camada densa final)  
- Dataset **Cats vs Dogs** (TFDS)  
- Data pipeline com pré-processamento e batching  
- Treinamento supervisionado e validação  
- Avaliação com métricas e gráficos  
- Teste com imagens externas  
- Salvamento do modelo em `.h5`

---

## 📂 Estrutura do Projeto
- **Notebook completo** com todas as etapas do treinamento  
- Código organizado em passos (preparação, dataset, modelo, treino, avaliação, teste e exportação)  
- Função de predição para imagens enviadas pelo usuário  
- Modelo final salvo: `modelo_gatos_cachorros.h5`  

---

## 📊 Resultados
O modelo final atingiu excelente desempenho:

- **Accuracy de treino:** ~98%  
- **Accuracy de validação:** ~98%  

O desempenho alto demonstra a eficiência do Transfer Learning mesmo sem GPU.


