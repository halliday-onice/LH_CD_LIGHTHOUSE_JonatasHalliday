# LH_CD_LIGHTHOUSE
Repositório destinado ao desafio LightHouse Indicium para Cientista de Dados

Para executar o projeto é necessário ter as seguintes bibliotecas instaladas  

import pandas as pd  

import numpy as np  

import seaborn as sns  

from matplotlib import pyplot as plt  

import shutil  

import geopandas as gpd  

import os  

from sklearn.tree import DecisionTreeRegressor  

from sklearn.linear_model import LinearRegression  

from sklearn.model_selection import train_test_split  

from sklearn.neighbors import KNeighborsRegressor  

from sklearn.metrics import accuracy_score  

from sklearn.linear_model import Ridge  

from sklearn.linear_model import Lasso  

from sklearn.metrics import mean_squared_error, r2_score  

from sklearn.model_selection import cross_val_score  

from sklearn.ensemble import RandomForestRegressor  

from sklearn.model_selection import GridSearchCV  

from sklearn.metrics import make_scorer, r2_score, mean_absolute_error, mean_squared_error,accuracy_score  

from sklearn.preprocessing import MinMaxScaler  

from sklearn.metrics import mean_squared_error  

Este repositório contém os seguintes arquivos:  

1) Notebook intitulado "aloacaoCarros.ipynb" contendo todo o código utilizado no projeto
2) Arquivo cars_train.csv utilizado no script  
3) Arquivo cars_test.csv também utilizado no script
4) Relatório de Análises Estatísticas em formato pdf
5) Arquivo predicted.csv contendo uma planilha contendo o id e o preço que foi predito


O projeto foi feito em um notebook na máquina local e portanto, é no formato de ipynb. O script é dividido em três partes principais:  

1) Setup das bibliotecas necessárias
2) limpeza e preenchimento de dados faltantes
3) Análise exploratória de dados
4) Transformação de dados categóricos em dados númericos
5) Exercício de regressão (previsão) do preço do veículo

Para rodar o projeto basta abrir o arquivo em uma máquina local com algum editor de texto que possua uma extensão capaz de ler arquivos no formato .ipynb ou com o google colab.  
Para rodar cada célula no notebook basta pressionar a tecla shift + enter(ou return)  


A divisão e resposta das perguntas nos itens citados no documento estão respondidas na forma de Markdown ao longo notebook.
   



