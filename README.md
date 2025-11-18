# Análise de Performance e Alcance de Redes Sociais

## Visão Geral do Projeto

Este projeto consiste na implementação e análise de um sistema de banco de dados projetado para monitorar, armazenar e analisar dados de **performance e alcance de redes sociais**. O objetivo principal é fornecer uma base de dados robusta e eficiente para extrair *insights* valiosos sobre o desempenho de conteúdo e o crescimento de perfis em diversas plataformas.

Para garantir a máxima flexibilidade e eficácia na manipulação de diferentes tipos de dados de redes sociais (estruturados e não estruturados), o projeto foi desenvolvido utilizando uma abordagem **híbrida**, implementando tanto um banco de dados relacional quanto um não relacional.

---

## Tecnologias Utilizadas

O projeto utiliza duas abordagens de banco de dados para otimizar o armazenamento e a recuperação de diferentes tipos de dados:

### 1. Banco de Dados Relacional (SQL)
* **Finalidade:** Armazenar dados altamente estruturados e relacionais, como informações de **usuários**, **perfis**, **métricas chave** (ex: contagem de seguidores, datas de publicação) e a manutenção de **relacionamentos** bem definidos entre as entidades.
* **Vantagens:** Garante **consistência** (ACID) e **integridade** referencial, crucial para métricas financeiras ou contagens exatas.
* **Tecnologia:** MySQL

### 2. Banco de Dados Não Relacional (NoSQL)
* **Finalidade:** Armazenar dados **não estruturados** ou **semi-estruturados** e de alta volumetria, como o conteúdo bruto e dados que mudam de esquema frequentemente.
* **Vantagens:** Oferece alta **escalabilidade horizontal**, **flexibilidade** de esquema e desempenho superior para operações de leitura/escrita em grandes volumes de dados.
* **Tecnologia:** MongoDB

---

## Foco na Análise de Dados

O banco de dados foi modelado pensando em facilitar consultas complexas e a geração de relatórios cruciais para a análise de performance:

* **Alcance e Impressões:** Medição da exposição e visualizações do conteúdo.
* **Engajamento:** Análise de curtidas, comentários, compartilhamentos e salvamentos.
* **Taxa de Conversão:** Identificação da eficácia das publicações em gerar ações desejadas.
* **Crescimento de Seguidores:** Monitoramento da evolução da base de usuários ao longo do tempo.
* **Análise de Conteúdo:** Classificação e agrupamento de posts por tema, formato ou *hashtag* para identificar padrões de sucesso.

---

## Colaboradores

* Lucas Alves dos Santos
* Bruno Cruz Voltezou
* Pedro Augusto da Silva Abreu
* Adham Juan S Araujo
