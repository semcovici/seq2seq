# Seq2Seq Date Conversion

Este repositório contém um trabalho desenvolvido para a conversão de datas usando modelos de Seq2Seq. O objetivo é transformar datas escritas em formato textual (como "27 dezembro 200") para um formato padronizado (como "27/12/2004"). 

## Estrutura do Projeto

Os experimentos e as análises realizadas para o desenvolvimento do modelo estão detalhados no notebook `notebooks/EP3.ipynb`. 

Os dados utilizados para treinamento e teste estão disponíveis no diretório `data/`.

## Instruções para Execução

Para executar o projeto, siga as etapas abaixo:

1. **Requisitos**
   - Certifique-se de estar usando Python 3.12.7.
   - Instale as dependências listadas em `requirements.txt`, preferencialmente em um ambiente virtual (e.g., conda ou venv).
   
2. **Word Embedding**
   - Baixe o modelo de embeddings Word2Vec disponibilizado pelo NILC: [link para download](http://nilc.icmc.usp.br/nilc/index.php/repositorio-de-word-embeddings-do-nilc).
   - Após o download, coloque o arquivo na pasta `models/embedding/`. Mais detalhes sobre essa etapa podem ser encontrados no notebook `notebooks/EP3.ipynb`.

## Estrutura de Pastas

- `data/`: contém os dados para o treinamento e teste.
- `models/embedding/`: onde o modelo Word2Vec deve ser armazenado.
- `notebooks/EP3.ipynb`: notebook com os experimentos e a análise dos resultados.