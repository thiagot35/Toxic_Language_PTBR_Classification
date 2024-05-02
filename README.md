# Toxic_Language_PTBR_Classification

# ML Olympiad - Toxic Language (PTBR) Detection

Competição do Kaggle para Classificação Binária entre tweets Tóxicos e Não Tóxicos em Português Brasileiro

https://www.kaggle.com/competitions/ml-olympiad-toxic-language-ptbr-detection/overview

Meu intuito ao entrar no desafio era exercitar na prática, em um cenário real, como utilizar uma rede neural para problemas de Classificação de texto.

Ao longo do desenvolvimento da solução utilizei conceitos e libs já conhecidas para tratamento de texto como remoção de stop words, correção ortográfica, tokenização, stemming e vetorizacão.

Desses destaco a biblioteca Symspell para a correção de palavras por funcionar através de Symmetric spelling correction que conheci através do artigo [A quick overview of the implementation of a fast spelling correction algorithm](https://medium.com/@agusnavce/a-quick-overview-of-the-implementation-of-a-fast-spelling-correction-algorithm-39a483a81ddc) por precisar de uma biblioteca que fizesse a correção ortográfica rapidamente.

Neste notebook, além do código, descrevi as etapas de desenvolvimento do modelo que separei nos tópicos abaixo:

# Tratamento dos Dados
## Dicionário para tratar "expressões de internet"
## Definição do Corpus para Correção das Palavras
## Correção de Palavras
### Exceções
### Funções para Tratamento

# Visualização dos Dados
## Word Cloud
## Quantidade de Palavras x Aparições na Base

# Treino e Validação do Modelo
## Rede Neural
## Regressão Logística

# Aplicação do Modelo
## Tratamento dos dados submetidos para a Competição
## Predição
