# qa-gdpr-compliance-project
Projeto de QA para validação ponta a ponta da conformidade com o RGPD: testes funcionais, API, dados, segurança e automação.

# QA + RGPD Compliance Project  
**Validação Técnica, Jurídica e Estruturada de Conformidade em Produtos Digitais**

Este projeto demonstra como um profissional de QA pode validar, de ponta a ponta, 
a conformidade de um sistema com o RGPD (Regulamento Geral de Proteção de Dados), 
unindo análise regulatória, testes funcionais, validação de APIs, fluxo de dados, 
segurança e automação.

A proposta do projeto é evoluir progressivamente da definição dos requisitos legais 
até a execução técnica dos testes, evidenciando como exigências jurídicas podem ser 
traduzidas em validações práticas aplicáveis a produtos digitais reais.

---

# 🧭 Estrutura Geral do Projeto

O projeto está organizado em **cinco etapas progressivas**, cada uma aprofundando o nível técnico e jurídico da validação.

## **🔵 Step 1 — Testes Funcionais + API Básica (Completo)**

Esta etapa é dedicada à transformação direta dos artigos do RGPD 
(Art. 7, 12, 15, 16, 17 e 19) em casos de teste estruturados.

O foco do Step 1 é a definição clara e técnica de:
- cenários de teste funcionais pela interface;
- cenários de teste de API como especificação técnica;
- mapeamento entre requisito legal → cenário → validação esperada.

Nesta etapa, os testes são descritos de forma detalhada, mas ainda não executados, 
servindo como base formal para a validação prática nos passos seguintes.

📂 Pasta: `/step-1-functional-and-api`

---

## **🟣 Step 2 — Análise Estrutural e Validação do Fluxo de Dados via API**

Nesta etapa, os casos de teste de API definidos no Step 1 passam a ser 
executados manualmente, com foco na validação real do fluxo de dados 
e do comportamento dos endpoints.

Inclui:
- execução manual de testes de API (ex.: Postman ou ferramenta equivalente);
- validação de autenticação, headers, status codes e payloads;
- análise de exposição e minimização de dados pessoais;
- mapeamento dos fluxos de dados entre endpoints;
- registro de evidências e resultados;
- identificação de falhas técnicas e riscos regulatórios.

Esta etapa representa a transição do design de testes para a validação prática, 
servindo de base para análises mais profundas nos Steps 3, 4 e 5.

📂 Pasta: `/step-2-api-data-analysis`

---

## **🟡 Step 3 — Dados, Logs e Auditoria Técnica**

Validação de consistência entre:

**API → Banco de Dados → Logs**

Inclui:
- Consultas SQL
- Verificação de integridade e coerência
- Análise de trilha de auditoria
- Rastreabilidade técnica

📂 Pasta: `/step-3-data-and-audit`

---

## **🔴 Step 4 — Segurança, RBAC e Incidente Simulado**
Validação de:
- perfis de acesso,
- tokens,
- erros seguros,
- tentativas de acesso indevido,
- resposta a incidente envolvendo dados pessoais.

📂 Pasta: `/step-4-security-and-incident`

---

## **🟢 Step 5 — Automação Essencial (Python + Pytest)**

Automação dos cenários críticos:

- API
- Direitos do titular
- Fluxos de dados sensíveis
- Validações repetíveis

📂 Pasta: `/step-5-automation`

---

# 🎯 Objetivo Final do Projeto

Criar um framework completo de QA especializado em:

- proteção de dados,
- validação técnica de conformidade,
- análise estrutural de APIs,
- auditoria e segurança,
- automação orientada a risco regulatório.

O resultado final é um projeto **profissional, replicável e alinhado ao mercado europeu**, demonstrando domínio técnico e entendimento profundo do RGPD aplicado a produtos digitais.

---

# 👤 Autor
Pedro — QA | Dados | Conformidade | RGPD  
