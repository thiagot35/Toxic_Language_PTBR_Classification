# ML Olympiad - Toxic Language (PTBR) Detection

Competição do Kaggle para Classificação Binária entre tweets Tóxicos e Não Tóxicos em Português Brasileiro

https://www.kaggle.com/competitions/ml-olympiad-toxic-language-ptbr-detection/overview

Meu intuito ao entrar no desafio era exercitar na prática, em um cenário real, como utilizar uma rede neural para problemas de Classificação de texto.

Ao longo do desenvolvimento da solução utilizei conceitos e libs já conhecidas para tratamento de texto como remoção de stop words, correção ortográfica, tokenização, stemming e vetorizacão.

Desses destaco a biblioteca Symspell para a correção de palavras por funcionar através de Symmetric spelling correction que conheci através do artigo [A quick overview of the implementation of a fast spelling correction algorithm](https://medium.com/@agusnavce/a-quick-overview-of-the-implementation-of-a-fast-spelling-correction-algorithm-39a483a81ddc) por precisar de uma biblioteca que fizesse a correção ortográfica rapidamente.

Neste notebook, além do código, descrevi as etapas de desenvolvimento do modelo que separei nos tópicos abaixo.

## Índice

1. ML Olympiad - Toxic Language (PTBR) Detection
3. Tratamento dos Dados
	1. Dicionário para tratar "expressões de internet"
	2. Definição do Corpus para Correção das Palavras
	3. Correção de Palavras
		1. Exceções
		2. Funções para Tratamento
4. Visualização dos Dados
	1. Word Cloud
	2. Quantidade de Palavras x Aparições na Base
5. Treino e Validação do Modelo
	1. Rede Neural
	2. Regressão Logística
6. Aplicação do Modelo
	1. Tratamento dos dados submetidos para a Competição
	2. Predição
