# Segmentação de Clientes
Projeto de aprendizagem não supervisionada, desenvolvido no Nanodegree de Data Scientist da Udacity, cujo objetivo é realizar a segmentação de clientes por meio da criação grupos (clusters) naturais através de seus comportamentos de compra.

### Instalação

Este projeto requer **Python 2.7** e as seguintes bibliotecas Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html) 


### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook finding_donors_PT.ipynb
```  
ou
```bash
jupyter notebook finding_donors_PT.ipynb
```

Isso abrirá o o software e arquivo de projeto iPython Notebook em seu navegador.

### Dados

O conjunto de dados consiste em 440 registros coletados dos clientes de um atacadista de Lisboa/Portugal,sendo que cada registro possui 8 atributos. Mais informações no reposítorio: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 