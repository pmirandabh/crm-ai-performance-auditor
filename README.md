# 🤖 CRM AI Performance Auditor

Sistema inteligente para auditoria comercial, análise de pipeline e suporte à tomada de decisão utilizando Inteligência Artificial.

---

## 📌 Visão Geral

O CRM AI Performance Auditor foi desenvolvido para auxiliar gestores comerciais na análise da saúde do funil de vendas, qualidade da execução comercial e acompanhamento da performance de vendedores.

A plataforma consolida dados do CRM, processa regras de negócio específicas e utiliza Inteligência Artificial para gerar análises consultivas, identificar riscos e sugerir ações para melhoria dos resultados comerciais.

---

## 🎯 Problema de Negócio

Em operações comerciais de alta escala, gestores enfrentam desafios como:

- Negociações esquecidas no pipeline.
- Falta de padronização no acompanhamento comercial.
- Dificuldade para identificar gargalos rapidamente.
- Baixa visibilidade da qualidade da execução dos vendedores.
- Grande volume de dados para análise manual.

Esses fatores impactam diretamente a previsibilidade de receita e a eficiência da operação comercial.

---

## 🚀 Solução

Desenvolvimento de uma plataforma inteligente capaz de:

- Avaliar automaticamente negociações em andamento.
- Identificar oportunidades em risco.
- Gerar score de qualidade comercial.
- Avaliar vendedores individualmente.
- Avaliar a saúde geral do pipeline.
- Fornecer recomendações assistidas por IA.
- Disponibilizar consultas conversacionais através de um chat inteligente.

---

## 🏗️ Arquitetura da Solução

```text
CRM (Ploomes)
       ↓
   APIs REST
       ↓
      n8n
       ↓
 Processamento
       ↓
 Banco de Dados
       ↓
 IA Generativa
       ↓
 Dashboard Web
       ↓
 Gestores Comerciais
```

---

## ⚙️ Automação e Orquestração

O n8n foi utilizado como camada central de automação para:

- Consumo de dados do CRM.
- Processamento das negociações.
- Aplicação das regras de negócio.
- Consolidação dos indicadores.
- Integração com serviços de IA.
- Atualização das análises.
- Sincronização das informações entre sistemas.

---

## 📊 Principais Funcionalidades

### 🎯 Score por Negócio

Avaliação individual das oportunidades com identificação de riscos e oportunidades de melhoria.

### 👤 Score por Vendedor

Avaliação consolidada da execução comercial de cada vendedor.

### 📈 Score do Pipeline

Análise da saúde geral do funil de vendas.

### 🚨 Identificação de Riscos

Detecção automática de negociações com baixa qualidade de acompanhamento.

### 🤖 Assistente de IA

Chat integrado para suporte à tomada de decisão com contexto dos dados analisados.

### 📋 Dashboard Gerencial

Visualização consolidada para acompanhamento da operação comercial.

---

## 🧠 Inteligência Artificial Aplicada

A IA foi configurada para atuar como uma consultora comercial digital, auxiliando gestores e vendedores através de:

- Feedbacks consultivos.
- Identificação de gargalos.
- Recomendações de ações.
- Priorização de oportunidades.
- Apoio estratégico à tomada de decisão.

O objetivo não é substituir a análise humana, mas acelerar a identificação de oportunidades e riscos dentro da operação.

---

## 🛠️ Tecnologias Utilizadas

- Inteligência Artificial Generativa
- CRM Ploomes
- APIs REST
- n8n
- Next.js
- React
- TypeScript
- Banco de Dados
- Dashboards Analíticos

---

## 👨‍💻 Minha Participação

Responsável pela concepção e estruturação completa da solução:

- Levantamento de requisitos.
- Definição das regras de negócio.
- Estruturação da arquitetura.
- Integração com CRM.
- Construção dos workflows de automação.
- Estruturação da lógica de scoring.
- Configuração dos modelos de IA.
- Desenvolvimento dos dashboards.
- Criação da experiência do usuário.
- Validação dos resultados junto às áreas de negócio.

---

## 📸 Capturas do Projeto

### 🔐 Tela de Login

![Tela Login](Tela%20Login.png)

### 📊 Dashboard Geral

![Dashboard Geral](Menu%20Tela%20Inicial.png)

### 📋 Lista de Negócios Analisados

![Negócios Analisados](Menu%20Lista%20de%20Negócios%20analisados.png)

### 🎯 Análise Individual do Negócio

![Análise do Negócio](Menu%20Analise%20do%20Negócio.png)

### 👤 Análise de Performance do Vendedor

![Análise do Vendedor](Menu%20Analise%20do%20Vendedor.png)

### 🤖 Assistente de IA

![Chat IA](Menu%20Chat%20IA.png)

![Chat IA 2](Menu%20Chat%20IA%202.png)

![Chat IA 3](Menu%20Chat%20IA%203.png)

---

## 📚 Aprendizados do Projeto

Durante o desenvolvimento desta solução foram aprofundados conhecimentos em:

- Arquitetura de sistemas orientados a dados.
- Integração de CRM via APIs.
- Construção de workflows complexos em n8n.
- Aplicação de IA em processos comerciais.
- Engenharia de prompts.
- Desenvolvimento de dashboards analíticos.
- Estruturação de regras de negócio para scoring.
- Experiência do usuário aplicada à análise de dados.

---

## 📈 Benefícios da Solução

- Maior visibilidade da operação comercial.
- Identificação rápida de gargalos.
- Melhoria na qualidade da execução comercial.
- Redução do tempo gasto em análises manuais.
- Apoio à tomada de decisão baseada em dados.
- Padronização dos critérios de acompanhamento comercial.

---

## 🔒 Confidencialidade

Por questões de confidencialidade e proteção de propriedade intelectual, informações estratégicas, algoritmos, integrações, regras de negócio detalhadas e dados operacionais foram anonimizados para publicação deste projeto.
