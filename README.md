# Atividade_Arquitetura

# Arquitetura proposta
![image](https://github.com/lucasconti888/Atividade_Arquitetura/assets/99270135/dc0018f5-ba95-44c6-88e1-9e0e2eaad346)


## 1 Entrada de dados

Como o projeto consiste na construção de um cubo de dados, existem 3 entradas de dados, sendo eles de 2 tipos:

1.  Dados da API do Cliente: Os dados são recebidos por meio da API do cliente e são encaminhados para processamento.
2.  Dados Públicos CSV: Dados em formato CSV são fornecidos como fontes de entrada.

## 2 Srcipts em Python

Após o recebimento de dados pela API do cliente, os dados passam pelo script em python para serem atualizados quando necessário. Já no caso dos dados em CSV, o script em python facilita a integração com o Data Lake.

## 3 Data Flow

Após o Data Lake, os dados são enviados para o serviço que desempenha o papel de ETL, o DataFlow.
O Dataflow é um serviço de processamento de dados em tempo real e em lote na nuvem. Ele permite que você processe grandes volumes de dados e pode ser usado como ETL em um pipeline de Big Data.

## BigQuery

O BigQuery é um serviço de armazenamento e análise de dados na nuvem que permite a execução de consultas SQL em conjuntos grandes de dados de forma rápida. É uma ferramenta  para análise de dados e geração de relatórios.
É para ele que os dados processados pelo ETL são enviados.

## Data Studio

O DataStudio é uma ferramenta de visualização de dados que permite criar relatórios interativos e painéis de controle a partir de dados diversos.

## Segurança

A segurança básica da arquitetura do cubo é feita pela Virtual Private Cloud (VPC), garantindo segurança e isolamento dos recursos. O Key Management permite o gerenciamento de acessos pela pipeline e o TLS é uma criptografia que impede o vazamento de informações trafegadas por ela.


## Tabela 
![image](https://github.com/lucasconti888/Atividade_Arquitetura/assets/99270135/e3b02f60-96f0-4d89-8cd2-53c06c2006a2)

