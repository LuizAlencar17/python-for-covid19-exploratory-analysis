## Guia do repositório

Este repositório foi criado para armazenar os códigos fontes do segundo projeto prático da disciplina "Redes Neurais Artificiais" 2020.1

Equipe: 
Bonifácio de Oliveira;
Luiz Felipe;
Luiz Fabio;
Rafaela Melo.


## Sobre os arquivos 

Os problemas propostos estão disponíveis em:

1) "Problemas.pdf".

Os Dataset's que foram utilizados estão disponíveis em:

1) "dataAll.txt";
2) "data1.txt";
3) "dataHoldout.txt".

Os problemas propostos pelo projeto prático foram alocados da seguinte forma: 

1) Problema da subseção 2.1;
2) Problema da subseção 2.2;
2) Problema da subseção 2.3.

Cada solução de um problema foi resolvido por um arquivo ".ipynb", sendo agrupados sequencialmente em:

1) "Parte 1.ipynb" -> Para o primeiro problema;
2) "Parte 2.ipynb" -> Para o segundo problema;
2) "Parte 3.ipynb" -> Para o terceiro problema.

## Sobre o Neurônio  

Bem, vamos entender um pouco sobre os principais atributos da classe de Neurônio construída.

```python
# Criação da classe neurônio
n = Neuronio ()

# Conjunto de dados do neurônio
n.dados
# Conjunto de dados de treinamento
n.x_treino
# Conjunto de dados de teste
n.x_teste
# Conjunto de pesos do neurônio
n.pesos
# Valor do ϑ
n.teta
# Valor da taxa de aprendizagem
n.ta
# Valor do viés
n.vies
# Conjunto de ajustes feitos
n.total_de_ajustes
# Valor do total de épocas
n.epocas
# Valores dos pontos para construir a reta gerada pelo neurônio
n.x1
n.x2

```
