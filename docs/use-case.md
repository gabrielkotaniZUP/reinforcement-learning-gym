# Use case

## Visão Geral:
Inicie sua jornada no mundo de **Reinforcement Learning** através da biblioteca do *Baseline3* com redes neurais já criadas.

## Pré-requisitos:
+ STK CLI
+ Python 3.7+
+ pip

## Inputs
Os inputs necessários para utilizar o template são:
| Campo | Valor | Descrição |
| Project name | Texto | Nome do projeto |

## Serviços:
+ `Tensorboard` : Ferramenta para visualizar métricas de treinamento.

## Portas:
+ `Tensorboard` : porta: 6006

## Quick-start:
### Inicie o ambiente virtual
```shell
pipenv shell
```

### Confirme se as bibliotecas foram instaladas
```shell
pip list
```

### Erros comuns...
+ Mac M1+ busque instalar com `conda-forge`
+ Verifique se instalou em um abiente virtual, é comum ter conflito com as versões de bibliotecas de DeepLearning como o PyTorch.
+ Tente instalar com Anaconda.

### Treine com `training.py`
```shell
Python3 -u training.py
```

### Accesse a pagina via browser
Abra um browser e acesse http://localhost:6006

### Rode com `training.py`
```shell
Python3 -u run.py
```