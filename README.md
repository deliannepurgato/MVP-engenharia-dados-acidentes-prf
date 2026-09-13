# MVP de Engenharia de Dados – Acidentes PRF 2025

Projeto desenvolvido como MVP da disciplina de Engenharia de Dados da
Pós-Graduação em Ciência de Dados e Analytics da PUC-Rio.

O projeto implementa um pipeline de Engenharia de Dados no Databricks para
análise dos acidentes registrados nas rodovias federais brasileiras em 2025,
utilizando dados públicos disponibilizados pela Polícia Rodoviária Federal (PRF).

## Arquitetura

O pipeline foi estruturado utilizando a arquitetura medalhão:

- **Bronze:** ingestão e armazenamento dos dados de origem;
- **Silver:** tratamento, padronização e validação da qualidade dos dados;
- **Gold:** construção do modelo dimensional em esquema estrela para análise.

## Tecnologias utilizadas

- Databricks
- SQL
- Delta Lake
- Arquitetura Medalhão
- Modelagem Dimensional
- GitHub

## Arquivos do projeto

- [Notebook do projeto](./MVP%20-%20Engenharia%20de%20Dados%20-%20Acidentes%20PRF%202025.ipynb)
- [Relatório completo do MVP](./MVP_Engenharia_Dados_Acidentes_PRF_2025.pdf)
- [Dataset utilizado](./datatran2025.csv)

## Fonte dos dados

Os dados utilizados neste projeto são provenientes do
[Portal de Dados Abertos da Polícia Rodoviária Federal (PRF)](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf),
considerando os acidentes agrupados por ocorrência referentes ao ano de 2025.

O arquivo `datatran2025.csv` utilizado no desenvolvimento do MVP também está disponível neste repositório.

## Pipeline

datatran2025.csv → Bronze → Silver → Gold → Análises

## Análises realizadas

O projeto busca responder questões relacionadas a:

- principais causas dos acidentes;
- dias e horários com maior número de ocorrências;
- estados e rodovias com maior concentração de acidentes;
- tipos de acidentes com maior número de vítimas fatais;
- condições meteorológicas e características da pista;
- características dos acidentes com vítimas fatais.

## Autora

Delianne Fernandes Purgato  
Pós-Graduação em Ciência de Dados e Analytics – PUC-Rio
