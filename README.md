# Modelo BERT como Classificador de Texto

Este projeto tem como intuito ajustar o modelo BERT para tarefas de classificação de texto, serão aplicadas duas abordagens:
- O BERT como um extrator de features, em que as features serão submetidas a um classificador comum.
- Será realizado o Fine-tuning do BERT treinando-o de fim a fim com os dados de entrada e uma camada de classificação.

A classificação será avaliada em dois datasets:
- Dmoz-Health: O DMOZ Health é um conjunto de dados derivado do DMOZ Open Directory Project (ODP), que era um dos maiores diretórios web organizados manualmente. Esse dataset contém informações categorizadas sobre sites relacionados à área da saúde.
- Dataset com dados de webscraping direcionados para o setor industrial.

Criar um classificador que seja robusto e que permita transitar entre os conjuntos de dados, pode auxiliar no processo de filtro de informações e identificar textos que sejam de interesse para determinado stakeholder.

## Utilização

O notebook aqui apresentado foi executado utilizando o ambiente de execução Google Colab para utilização de GPU (com acesso a um CUDA de 15GB RAM), facilitando o processo de treinamento e multiplicação de matrizes necessário.
