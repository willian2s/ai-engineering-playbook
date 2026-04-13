# 📄 AI Prompts

Este diretório contém os prompts oficiais utilizados no projeto.

Cada prompt tem um papel específico dentro do ciclo de vida da engenharia.

---

# 🧠 Visão geral

| Prompt                      | Objetivo                         |
| --------------------------- | -------------------------------- |
| generate-rules-auto         | Criar regras automaticamente     |
| generate-rules-with-context | Criar regras com contexto manual |
| update-rules                | Atualizar regras existentes      |
| audit-architecture          | Auditar sistema completo         |

---

# 🥇 generate-rules-auto.md

## 📌 Objetivo

Gerar automaticamente:

- `.rules`
- `AGENTS.md`
- `CLAUDE.md`
- `.github/copilot-instructions.md`

A partir da análise do código.

---

## 🧠 Quando usar

- Setup inicial do projeto
- Primeira adoção de AI
- Após grandes mudanças estruturais

---

## 🤖 Modelo recomendado

- GPT-5.4

---

## 📝 Commit

```
feat(ai): generate initial AI rules based on repository analysis
```

---

# 🥈 generate-rules-with-context.md

## 📌 Objetivo

Gerar regras com base em contexto fornecido manualmente.

---

## 🧠 Quando usar

- Refinar regras
- Projetos complexos
- Ajustes arquiteturais específicos

---

## 🤖 Modelo recomendado

- GPT-5.4

---

## 📝 Commit

```
feat(ai): generate AI rules with explicit project context
```

---

# 🥉 update-rules.md

## 📌 Objetivo

Atualizar regras existentes com base na evolução do código.

---

## 🧠 Quando usar

- Após refactors
- Após adicionar serviços
- Quando AI começa a errar
- Mudança de arquitetura

---

## 🤖 Modelo recomendado

- GPT-5.4

---

## 📝 Commit

```
chore(ai): update AI rules based on architecture changes
```

---

# 🔥 audit-architecture.md

## 📌 Objetivo

Executar auditoria técnica completa:

- arquitetura
- tech debt
- riscos
- escalabilidade
- integrações

---

## 🧠 Quando usar

- Revisão técnica
- Planejamento de refactor
- Onboarding técnico
- Diagnóstico de problemas

---

## 🤖 Modelo recomendado

- GPT-5.4 (principal)
- Claude Sonnet / Opus (alternativo)

---

## 📝 Commit

```
docs(ai): add architecture audit report
```

ou

```
chore(ai): update architecture audit
```

---

# 🧠 Boas práticas

- Sempre usar modelos fortes para análise
- Revisar resultados antes de aplicar
- Versionar mudanças relevantes
- Manter prompts atualizados com o projeto

---

# 🏁 Conclusão

Esses prompts são parte da arquitetura do projeto.

Devem ser utilizados de forma consistente para garantir:

- qualidade
- padronização
- evolução contínua
