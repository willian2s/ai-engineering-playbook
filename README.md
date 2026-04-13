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

| Categoria        | % de uso    | Objetivo                    |
| ---------------- | ----------- | --------------------------- |
| ⚡ Leve (Flow)   | 70–80%      | Velocidade e produtividade  |
| 🧠 Intermediário | 15–25%      | Desenvolvimento padrão      |
| 🔥 Avançado      | 5–10%       | Análise e decisões críticas |
| 🤖 Agent         | Sob demanda | Automação e execução        |

---

## ⚡ Tarefas leves (70–80%)

| Ferramenta     | Modelos recomendados | Quando usar                   |
| -------------- | -------------------- | ----------------------------- |
| GitHub Copilot | GPT-5.1-mini         | Autocomplete, funções simples |
| OpenAI         | GPT-5 mini           | CRUD, código repetitivo       |
| Claude         | Claude Haiku         | Ajustes rápidos               |

---

## 🧠 Desenvolvimento padrão (15–25%)

| Ferramenta     | Modelos recomendados | Quando usar        |
| -------------- | -------------------- | ------------------ |
| GitHub Copilot | GPT-5.4              | Features completas |
| GitHub Copilot | Claude Sonnet        | Código mais limpo  |
| OpenAI         | GPT-5.4              | APIs, validações   |
| Claude         | Claude Sonnet        | Regras de negócio  |

---

## 🔥 Problemas complexos (5–10%)

| Ferramenta     | Modelos recomendados | Quando usar                    |
| -------------- | -------------------- | ------------------------------ |
| GitHub Copilot | GPT-5.4              | Debugging complexo             |
| OpenAI         | GPT-5.4              | Análise de múltiplos arquivos  |
| Claude         | Claude Sonnet / Opus | Arquitetura, decisões críticas |

---

## 🤖 Agent / automação (sob demanda)

| Ferramenta     | Modelos recomendados | Quando usar            |
| -------------- | -------------------- | ---------------------- |
| OpenAI         | GPT-5.3 Codex        | Refactor multi-arquivo |
| GitHub Copilot | Codex (agent)        | Execução assistida     |
| Claude         | Claude (agent tools) | Análise + execução     |

---

## ⚖️ Regra geral

- Use modelos leves para velocidade
- Use modelos fortes para análise
- Use agentes para escala

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
- Regras são parte do sistema
- Segurança > velocidade
- Clareza > complexidade

---

# 🏁 Conclusão

Este setup permite:

- padronização de AI no time
- redução de erro
- melhoria contínua da arquitetura
- uso consistente entre ferramentas (Zed, Copilot, etc.)
