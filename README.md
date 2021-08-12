# Data-Science-and-Big-Data-TCC
Code and Data for GOAU4 stock prices univariate and multivariate models 

#PORTUGUESE DESCRIPTION
O objetivo do trabalho foi mostrar o domínio de três técnicas para o desenvolvimento de séries temporais: Univariate Autoregression, Univariate RNN model e Multivariate RNN model.

Um segundo objetivo, ao meu ver mais importante que o anterior, foi esclarecer como um modelo deve ser usado, depois de desenvolvido, já que ao longo do trabalho deparei com vários tutoriais que desenvolvem perfeitamente o modelo, mas depois usam os dados de teste na obtenção das predições. Isso melhora significativamente os indicadores, porém não está correto: as estimativas de TODA a série temporal devem ser feitas sem o conhecimento dos dados de teste, com uso APENAS dos dados de treinamento e das previsões já calculadas.

Este repositório contém o material (código e dados) usado para o desenvolvimento do TCC para a pós-graduação em Ciência de Dados e Big Data na PUC-MG.

O material se divide em dois notebooks (jupyter notebook): um contém análises comparativas entre 6 ativos, exploração inicial dos dados e análises univariadas para GOAU4.
O segundo contém apenas a análise multivariada para GOAU4, com a inclusão de dados de números de casos de Covid no Brasil.

Os links para a obtenção dos dados constam do material, mas o material baixado usado na análise foi incluído neste repositório.

#ENGLISH DESCRIPTION
The goal in this work is demonstrate my expertise in developing time series using three techniques: Univariate Autoregression, Univariate RNN model and Multivariate RNN model.

A second and even more important goal is to clarify how a model should be used, after trained and achieving good performance: along this job, I had found tutorials that teach with great detail how to develop and train a model. Surprisingly, in the step of calculating predictions, they concatenate train and test data and produce predictions using test data! This makes the model to achieve excellent performance, but it is no right. All time series predictions should be calculated without any knowledge about test data. ONLY train data and previous predictions can be used to achieve a new prediction.

This repository contains two notebooks (1. general exploration and univariate models and 2. Multivariate model) and the data used in these notebooks (references for the sources of the data are provided). This is the material used to develop the final work for my post-graduation in Data Sciences and Big Data at PUC-MG, Brazil.

