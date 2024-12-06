# openmetadata-docker-project

Este projeto é voltado para o estudo de ferramentas de engenharia e orquestração de dados, como [OpenMetadata](https://open-metadata.org/), [Apache Airflow](https://airflow.apache.org/) e [Trino](https://trino.io/) rodando em containers Docker.

O OpenMetadata serve como o núcleo do gerenciamento de metadados, enquanto o Airflow gerencia pipelines de dados e o Trino possibilita consultas distribuídas e de alto desempenho. Este projeto simula um cenário real de ingestão de dados, armazenamento em um banco relacional (MySQL) e execução de queries distribuídas, utilizando containers Docker para garantir portabilidade e reprodutibilidade.

## Estrutura do Projeto

```plaintext
openmetadata-docker-project/
├── data/
│   ├── arquivos.csv        # Arquivos CSV usados para popular o MySQL
├── docker-compose.yml      # Configuração dos containers Docker
└── README.md               # Documentação do projeto