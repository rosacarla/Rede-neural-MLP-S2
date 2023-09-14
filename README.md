# 🧠 TESTE DE REDE NEURAL MLP 
<p align="justify">Projeto de rede neural <i>Multi-Layer Perceptron</i> (MLP) para identificar números escritos (ou desenhados) manualmente por seres humanos em tarefa de visão computacional. Realizaram-se treinos com 2 até 10 neurônios na camada oculta, os quais foram acrescentados um a um.</p>
<p align="justify">Na parte final do notebook, apresenta-se a análise do modelo quanto a: métricas, parâmetros configuráveis, melhorias possíveis da arquitetura da rede para obter melhoria do seu desempenho.</p>  

## 🧰 Tecnologias utilizadas  
```python
# Importa bibliotecas
import matplotlib.pyplot as plt  # Necessario instalar matplotlib (Spyder, pip)
import numpy as np
import tensorflow as tf  # Necessario atualizar devido conflito em metricas
from keras.src.layers import Dense
from sklearn.model_selection import train_test_split
import tensorflow._api.v2 as tf  # Necessario para ajustar "compat"
import tensorflow.compat.v2 as tf # Necessario por erro de execução no Spyder
from tensorflow.keras import Sequential
```
---  

## ©️ Licença  
Distribuído sob a licença MIT. Veja `LICENSE`para informações adicionais.  

---  

## 📬 Contato  
Autora: Carla Edila Silveira  
E-mail:  rosa.carla@pucpr.edu.br

---
