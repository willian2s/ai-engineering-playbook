# 🤖 AI Engineering Playbook

Este repositório define um sistema estruturado para uso de IA no desenvolvimento de software.

O objetivo é transformar IA em uma **ferramenta previsível, consistente e escalável**, evitando respostas aleatórias e garantindo qualidade de engenharia.

---

# 🎯 Objetivo

Padronizar:

* como problemas são analisados
* como soluções são planejadas
* como código é gerado
* como decisões técnicas são tomadas
* como escalar uso de IA com segurança

---

# 🧠 Filosofia

A IA deve operar como um engenheiro sênior que:

* pensa antes de agir
* planeja antes de executar
* trabalha de forma incremental
* valida impacto
* evita complexidade desnecessária

---

# 📁 Estrutura do projeto

```
/ai
  /rules
    .rules
    AGENTS.md
    CLAUDE.md
    .github/
      copilot-instructions.md

  /prompts
    /core
      generate-rules-auto.md
      generate-rules-with-context.md
      update-rules.md
      audit-architecture.md

    /planning
      README.md
      problem-breakdown.md
      validation-planner.md
      execution-planner.md

    /execution
      backend-pattern.md
      frontend-pattern.md

  /playbooks
    decision-matrix.md
    escalation-playbook.md
    tooling-guide.md
```

---

# ⚙️ Fluxo principal

```bash
problem → breakdown → validation → execution → código
```

---

# 🧠 Etapas do sistema

## 1. Problem Breakdown (opcional)

Usado quando:

* o problema não está claro
* envolve múltiplos sistemas
* existe risco técnico

👉 Resultado: entendimento profundo do problema

---

## 2. Validation Planner (opcional)

Usado quando:

* a task é crítica
* existe risco de erro
* o fluxo é complexo

👉 Resultado: plano validado e seguro

---

## 3. Execution Planner (CORE)

Sempre que possível, use este passo.

Responsável por:

* transformar problema em plano executável
* identificar riscos
* gerar bloco pronto para execução

👉 Output: plano + bloco pronto para uso

---

## 4. Execução

### Fluxo padrão (80–90%)

```bash
execution-planner → Copilot → código
```

---

### Fluxo com controle (quando necessário)

```bash
execution-planner → template → Copilot
```

---

### Escalonamento (casos complexos)

```bash
Copilot falha → Codex / modelo mais forte
```

---

# 🧱 Templates (Execution)

Os templates são **opcionais** e usados como mecanismo de controle.

Use quando:

* o agente começa a se perder
* precisa garantir padrão arquitetural
* código precisa ser altamente consistente

---

# 📘 Playbooks

## Decision Matrix

Define:

* quando usar cada modelo
* quando escalar
* nível de complexidade

---

## Escalation Playbook

Define gatilhos claros:

* Copilot falhou 2x
* múltiplos arquivos envolvidos
* fluxo externo (API, pagamento, etc.)
* lógica crítica

---

## Tooling Guide

Define como usar:

* Copilot
* Codex
* outros modelos

---

# 🤖 Uso de IA

## Fluxo ideal

```bash
1. Pensar → planner
2. Validar → (opcional)
3. Executar → Copilot
4. Escalar → Codex (se necessário)
```

---

# ⚖️ Regras importantes

* Nunca codar sem entender
* Evitar mudanças grandes sem necessidade
* Priorizar clareza sobre complexidade
* Sempre considerar impacto
* Reutilizar padrões existentes

---

# 💡 Princípio central

> IA não deve substituir engenharia
> IA deve amplificar engenharia

---

# 🏁 Conclusão

Este sistema garante:

* mais previsibilidade
* menos bugs
* menos retrabalho
* melhor uso de IA
* maior consistência entre devs

---

# 🚀 Como começar

1. Pegue uma task
2. Rode o `execution-planner`
3. Use o output diretamente no Copilot
4. Use templates apenas se necessário

---

Isso é tudo que você precisa para usar IA como um engenheiro sênior.
