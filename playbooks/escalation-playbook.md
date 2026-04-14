# 🚨 AI ESCALATION PLAYBOOK

Este documento define regras objetivas para uso de ferramentas de IA no desenvolvimento.

O objetivo é garantir produtividade com Copilot como padrão e Codex como ferramenta de escalonamento.

---

## 🧠 PRINCÍPIO CENTRAL

- 🟦 Copilot = execução padrão
- 🟢 Codex = execução escalada (somente quando necessário)
- ❌ Nenhuma tarefa deve ir direto para Codex sem critério

---

## ⚙️ FLUXO OBRIGATÓRIO

### 1. Sempre começar com Copilot

Toda tarefa deve iniciar no Copilot, sem exceção.

---

### 2. Escalar somente se critérios forem atendidos

Codex só pode ser usado quando pelo menos UM gatilho for verdadeiro.

---

## 🔁 GATILHOS DE ESCALONAMENTO (OBJETIVOS)

### 🧠 1. FALHA REPETIDA

Escalar se:

- 2 tentativas no Copilot não resolveram o problema
- ou solução aplicada não corrigiu o comportamento esperado

---

### 📦 2. MULTI-ARQUIVO

Escalar se:

- alteração envolve mais de 3 arquivos
- ou impacto atravessa múltiplos módulos

---

### 🌐 3. DEPENDÊNCIA EXTERNA

Escalar se envolver:

- APIs externas
- integrações com terceiros
- eventos, filas, webhooks
- comunicação entre sistemas diferentes

---

### ⚠️ 4. LÓGICA CRÍTICA

Escalar se afetar:

- regras de negócio centrais
- fluxos críticos
- dados sensíveis ou financeiros
- consistência do sistema

---

### 🧩 5. AMBIGUIDADE TÉCNICA

Escalar se:

- causa raiz não está clara
- múltiplas hipóteses possíveis existem
- debug exige investigação ampla

---

## 🚫 PROIBIÇÕES

Não escalar para Codex quando:

- tarefa for local e simples
- mudança for de sintaxe ou ajuste pequeno
- problema já estiver claramente identificado

---

## 🧠 REGRA FINAL

Se houver dúvida:

👉 tente primeiro no Copilot

Se falhar ou se encaixar em qualquer gatilho:

👉 escale para Codex

---

## 🎯 OBJETIVO FINAL

- maximizar velocidade no Copilot
- usar Codex apenas como ferramenta de profundidade
- evitar desperdício de contexto e tempo
