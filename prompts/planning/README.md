# 🧠 Planning Prompts

Esta pasta contém os prompts responsáveis por transformar problemas em execução técnica estruturada.

Eles formam um pipeline completo de engenharia assistida por IA.

---

## 🎯 Objetivo

Padronizar como problemas são:

1. Entendidos
2. Validados
3. Transformados em planos executáveis

---

## ⚙️ Fluxo oficial

```bash
problem → breakdown → validation → execution → código
```

---

## 🧠 Etapas detalhadas

### 1. 🧠 Problem Breakdown (`problem-breakdown.md`)

#### 📌 Objetivo

Entender profundamente o problema antes de qualquer execução.

#### 🧠 Quando usar

* Problema não está claro
* Existe risco técnico
* Envolve múltiplas partes
* Pode impactar dados ou fluxo crítico

---

### 2. 🔍 Validation Planner (`validation-planner.md`)

#### 📌 Objetivo

Revisar criticamente o plano antes da execução.

#### 🧠 Quando usar

* Task crítica
* Fluxo complexo
* Existe risco de inconsistência
* Você quer evitar erro antes de codar

---

### 3. ⚙️ Execution Planner (`execution-planner.md`)

#### 📌 Objetivo

Transformar o problema em um plano executável.

#### 🧠 Quando usar

* Problema já está claro
* Plano já foi validado (ou é simples)
* Vai iniciar implementação

---

### 4. 💻 Implementação

#### Ferramentas

* Copilot → execução padrão
* Codex → problemas complexos

---

## 🚀 Fluxos práticos

### 🟢 Fluxo simples (80%)

```bash
execution-planner → Copilot → pronto
```

---

### 🔴 Fluxo completo (20%)

```bash
problem-breakdown
→ validation-planner
→ execution-planner
→ Copilot
→ Codex (se necessário)
```

---

## ⚖️ Regra de decisão rápida

```bash
Simples → execution
Complexo → breakdown → validation → execution
```

---

## 💡 Princípios

* Não codar sem entender
* Validar antes de executar quando houver risco
* Clareza reduz erro
* Execução estruturada reduz retrabalho

---

## 🧠 Filosofia

Separação de responsabilidades:

* 🧠 Pensar → breakdown
* 🔍 Validar → validation
* ⚙️ Executar → execution
* 💻 Implementar → ferramentas

---

## 🏁 Conclusão

Este fluxo garante:

* menos bugs
* menos retrabalho
* mais velocidade com segurança
* uso eficiente de IA
