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

# 🧠 Modelos recomendados

| Tipo de tarefa       | Modelo recomendado              |
| -------------------- | ------------------------------- |
| Geração de rules     | GPT-5.4                         |
| Atualização de rules | GPT-5.4                         |
| Auditoria técnica    | GPT-5.4 ou Claude (Sonnet/Opus) |
| Uso leve / testes    | GPT-5.1-mini                    |

📌 Regra geral:

- Use modelos fortes para tarefas de análise
- Use modelos leves apenas para tarefas simples

---

# 📄 Prompts

---

## 🥇 generate-rules-auto.md

### 📌 Objetivo

Gerar automaticamente:

- `.rules`
- `AGENTS.md`
- `CLAUDE.md`
- `.github/copilot-instructions.md`

A partir da análise do código.

### 🧠 Quando usar

- Setup inicial do projeto
- Primeira adoção de AI
- Após grandes mudanças estruturais

### 🤖 Modelo recomendado

- GPT-5.4

### 📝 Commit (Commitizen)

```
feat(ai): generate initial AI rules based on repository analysis
```

---

## 🥈 generate-rules-with-context.md

### 📌 Objetivo

Gerar regras com base em contexto fornecido manualmente.

### 🧠 Quando usar

- Refinar regras
- Projetos complexos
- Ajustes arquiteturais específicos

### 🤖 Modelo recomendado

- GPT-5.4

### 📝 Commit

```
feat(ai): generate AI rules with explicit project context
```

---

## 🥉 update-rules.md

### 📌 Objetivo

Atualizar regras existentes com base na evolução do código.

### 🧠 Quando usar

- Após refactors
- Após adicionar serviços
- Quando AI começa a errar
- Mudança de arquitetura

### 🤖 Modelo recomendado

- GPT-5.4

### 📝 Commit

```
chore(ai): update AI rules based on architecture changes
```

---

## 🔥 audit-architecture.md

### 📌 Objetivo

Executar auditoria técnica completa:

- arquitetura
- tech debt
- riscos
- escalabilidade
- integrações

### 🧠 Quando usar

- Revisão técnica
- Planejamento de refactor
- Onboarding técnico
- Diagnóstico de problemas

### 🤖 Modelo recomendado

- GPT-5.4 (principal)
- Claude Sonnet / Opus (alternativo)

### 📝 Commit (se versionar o resultado)

```
docs(ai): add architecture audit report
```

ou

```
chore(ai): update architecture audit
```

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
