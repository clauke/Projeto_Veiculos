# Projeto Veículos – Análise de Dados de Aluguel com Python e Spark

## 📌 Contexto de Negócio
Plataformas de mobilidade urbana que operam com veículos elétricos, como bicicletas e patinetes, geram grandes volumes de dados diariamente. A análise desses dados é fundamental para entender padrões de uso, comportamento dos usuários e eficiência operacional.

Este projeto simula um cenário de **Big Data aplicado ao aluguel de veículos elétricos**, com foco no uso de processamento distribuído para análise de grandes volumes de dados.

---

## 🎯 Objetivos do Projeto
- Simular um ambiente de Big Data com grande volume de registros  
- Utilizar o framework **Apache Spark** para processamento distribuído  
- Realizar ETL e análises exploratórias em larga escala  
- Demonstrar o uso de DataFrames Spark em linguagem Python  

---

## 📊 Base de Dados
Foi criado um **dataset fictício** contendo aproximadamente **700 mil registros**, representando operações de aluguel de veículos elétricos (bicicletas e/ou patinetes).

As variáveis simulam informações como:
- Perfil do usuário  
- Veículo utilizado  
- Loja de retirada e devolução  
- Data e hora de aluguel  
- Data e hora de devolução  

Para fins de demonstração e replicação, o repositório inclui uma **amostra do dataset com 50 mil registros**, em formato CSV.

---

## 🔎 Processamento e Análises (Python + Spark)
O projeto foi desenvolvido em **Python**, utilizando o framework **Apache Spark**, contemplando as seguintes etapas:

- Criação do `SparkContext`  
- Leitura do arquivo CSV em um DataFrame Spark  
- Limpeza e transformação dos dados (ETL)  
- Análises exploratórias em larga escala  
- Aplicação de métodos e operações sobre DataFrames Spark  

O foco principal está no **processamento distribuído** e na manipulação eficiente de grandes volumes de dados.

---

## 🛠️ Tecnologias Utilizadas
- Python  
- Apache Spark  
- PySpark  
- Jupyter Notebook  
- Sublime Text  

---

## ▶️ Como Executar o Projeto
1. Baixar os arquivos do repositório  
2. Abrir o arquivo `Projeto_Veiculos.ipynb` em um ambiente com Spark configurado  
3. Executar as células para criação do SparkContext, carregamento e análise dos dados  
4. Utilizar o arquivo `Amostra_dataset.csv` para testes e validações  

---

## 🧠 Considerações Finais
Este projeto tem como principal objetivo demonstrar o uso do **Apache Spark** aplicado à análise de grandes volumes de dados, explorando o potencial do processamento distribuído para tarefas de ETL e análise exploratória.

Por se tratar de um dataset fictício, os resultados têm caráter demonstrativo, com foco na **arquitetura da solução**, no uso do framework Spark e na escalabilidade do processamento.

---

## 👩‍💻 Autora
**Cláudia Kênia da Silva**  
Data Analyst | BI & Analytics  
