# 🤖 AI Engeneering Playbook

Este diretório contém os prompts oficiais para uso de IA no projeto.

O objetivo é padronizar:

- geração de regras
- evolução das regras
- auditoria técnica
- uso consistente de AI no time

---

# 📁 Estrutura

```
/ai
  /prompts
    generate-rules-auto.md
    generate-rules-with-context.md
    update-rules.md
    audit-architecture.md
```

---

# 🧠 Uso de modelos (recomendado)

## 📊 Distribuição de uso

| Categoria       | % de uso | Objetivo                 |
| --------------- | -------- | ------------------------ |
| ⚡ Médio (Flow) | 60–70%   | Desenvolvimento e edição |
| 🔥 Alto         | 20–30%   | Debugging e análise      |
| 🤖 Agent        | 5–10%    | Execução e automação     |
| 🧠 Refinamento  | Contínuo | Qualidade e arquitetura  |

---

## ⚡ Médio (Flow)

| Modelo        | Quando usar                           |
| ------------- | ------------------------------------- |
| GPT-5.1-mini  | CRUD, ajustes, código repetitivo      |
| GPT-5.4       | Features completas, lógica de negócio |
| Claude Sonnet | Código mais limpo, melhor estrutura   |

👉 Uso típico:

- inline edit
- desenvolvimento normal
- implementação de features

---

## 🔥 Alto (Análise e Debugging)

| Modelo        | Quando usar                              |
| ------------- | ---------------------------------------- |
| GPT-5.4       | Debugging complexo, múltiplos arquivos   |
| Claude Sonnet | Análise de código, entendimento profundo |
| Claude Opus   | Problemas difíceis e não óbvios          |

👉 Uso típico:

- investigação de bugs
- leitura de fluxo completo
- análise cross-service

---

## 🤖 Agent (Execução)

| Modelo         | Quando usar                       |
| -------------- | --------------------------------- |
| GPT-5.3 Codex  | Refactor multi-arquivo, automação |
| Claude (Agent) | Execução + análise combinada      |

👉 Uso típico:

- mudanças estruturais
- edição em múltiplos arquivos
- automação de tarefas

---

## 🧠 Refinamento (Qualidade e Arquitetura)

| Modelo        | Quando usar                           |
| ------------- | ------------------------------------- |
| Claude Sonnet | Refactor elegante, melhoria de código |
| Claude Opus   | Arquitetura, decisões críticas        |
| GPT-5.4       | Validação técnica e trade-offs        |

👉 Uso típico:

- revisão de código
- melhoria de arquitetura
- simplificação de lógica
- validação de decisões

---

## ⚖️ Regra geral

- GPT → velocidade, execução e escala
- Claude → qualidade, clareza e arquitetura
- Codex → automação e execução multi-arquivo

---

# 🧠 Boas práticas

## 1. Não usar modelo fraco para análise

Evite usar GPT-5.1-mini para:

- auditoria
- geração de rules
- decisões arquiteturais

---

## 2. Revisar sempre o output

AI não substitui revisão técnica.

Sempre valide:

- regras críticas
- fluxos de pagamento
- integrações externas

---

## 3. Versionar mudanças importantes

Rules fazem parte da arquitetura.

Mudanças devem ser commitadas.

---

## 4. Rodar update periodicamente

Recomendado:

- a cada refactor relevante
- a cada nova feature crítica
- mensalmente (mínimo)

---

## 5. Evitar rules genéricas

Se estiver genérico, refine com:

- contexto
- exemplos reais do código

---

# 🔁 Workflow recomendado

1. Gerar rules (auto)
2. Refinar com contexto
3. Commit inicial
4. Evoluir com update-rules
5. Rodar auditoria periodicamente

---

# 🧠 Filosofia

- AI é uma extensão da engenharia
- Use GPT para fazer
- Use Claude para pensar
- Use Agents para escalar
- Clareza > complexidade
- Segurança > velocidade

---

# 🏁 Conclusão

Este setup permite:

- padronização de AI no time
- redução de erro
- melhoria contínua da arquitetura
- uso consistente entre ferramentas (Zed, Copilot, etc.)
- melhor aproveitamento dos modelos disponíveis
- equilíbrio entre velocidade e qualidade
- evolução contínua da arquitetura
