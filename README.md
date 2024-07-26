# Consistência dos Metadados 

Este branch é dedicado à análise e manutenção da consistência dos metadados, utilizando o dataframe `ecommerce-product-images-18k`.

## Objetivo

Garantir a integridade e a consistência dos metadados, facilitando análises e processos de ETL (Extract, Transform, Load).

## Bibliotecas utilizadas para essa etapa

`Exiftool`
> Utilizado para ler os arquivos.

`Colorgram`
> Utilizada para extrair as cores predominantes em um conjunto de imagens.

`OpenCV`
> É uma biblioteca amplamente utilizada em Visão Computacional. Nesse contexto, foi executada para recortar as imagens, de forma que os fundos neutros nelas presentes, não afetassem o levantamento de cores predominantes em cada categoria.

## DataSet
O dataset utilizado para esse experimento, está presente, na integra,[aqui](https://www.kaggle.com/datasets/fatihkgg/ecommerce-product-images-18k).

