# 💊 Farmácia Virtual com AWS  
### Redução de Custos Operacionais em um Ambiente de Nuvem

## 📌 Visão Geral
Este projeto apresenta o desenvolvimento de uma **plataforma virtual para uma farmácia fictícia**, com foco na **redução de custos operacionais** por meio do uso eficiente de serviços da **AWS (Amazon Web Services)**.

A solução simula um cenário real de negócio, integrando **visualização de dados**, **gestão de produtos**, **cálculo de faturamento** e **boas práticas de computação em nuvem**, permitindo aplicar conceitos teóricos em um contexto prático e dinâmico.

---

## 🎯 Objetivos do Projeto
- Simular o funcionamento básico de uma farmácia
- Trabalhar com dados reais de produtos, preços e estoque
- Calcular faturamento, custos e lucro estimado
- Propor uma arquitetura em nuvem focada em **otimização de custos**
- Consolidar conhecimentos iniciais em AWS e Cloud Computing

---

## 🧪 Funcionalidades
- 📊 Visualização de produtos em estoque  
- 💰 Cálculo de faturamento estimado por produto  
- 📉 Análise de custos e lucro  
- 🗂️ Uso de dados estruturados em planilha (CSV)  
- ☁️ Arquitetura AWS pensada para reduzir gastos operacionais  

---

## ☁️ Serviços AWS Abordados (conceitual)
- **Amazon S3** – Hospedagem do frontend e armazenamento de dados  
- **AWS Lambda** – Processamento backend sem servidores dedicados  
- **Amazon RDS** – Banco de dados gerenciado  
- **Amazon CloudWatch** – Monitoramento e observabilidade  
- **AWS Cost Explorer** – Análise e controle de custos  

---

## 📂 Estrutura do Projeto

farmacia-virtual-aws/
│
├── README.md
├── data/
│ └── produtos_farmacia.csv
│
├── src/
│ ├── frontend/
│ │ └── index.html
│ └── backend/
│ └── backend.py
│
├── infra/
│ └── arquitetura-aws.md
│
└── docs/
└── estrategia-reducao-custos.md


---

## 🖥️ Interface
A interface foi desenvolvida em **HTML e CSS**, simulando um **dashboard de farmácia**, onde é possível visualizar:
- Lista de produtos
- Categorias
- Preços de venda
- Estoque
- Faturamento estimado

> Em um ambiente real, esses dados seriam consumidos diretamente do S3 ou de um banco RDS.

---

## 🧠 Estratégias de Redução de Custos
- Uso de arquitetura **serverless** para evitar servidores ociosos
- Armazenamento de arquivos estáticos no S3
- Monitoramento contínuo de recursos
- Escalonamento sob demanda
- Eliminação de serviços não utilizados

---

## 🚀 Conclusão
Este projeto demonstra como decisões corretas de arquitetura em nuvem podem impactar diretamente na **eficiência operacional e redução de custos** de um negócio.

Além de atender aos requisitos do desafio, a solução serve como base para evolução futura, podendo incorporar APIs, autenticação, banco de dados real e deploy completo na AWS.

---

📘 **Projeto desenvolvido como desafio prático para aplicação de conceitos iniciais de AWS e Cloud Computing.**

---

## 👩‍💻 Autora

Feito com 💛 por Bruna Guimarães

--- 

## 🌟 Apoie o projeto

Se você gostou, não esqueça de deixar um ⭐ no repositório! Isso ajuda muito o projeto a crescer e me incentiva a continuar criando. 🙌


