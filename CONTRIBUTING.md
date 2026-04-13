# 🤝 Contributing Guide

Este projeto adota uma abordagem **AI-assisted engineering**.

O uso de Inteligência Artificial (AI) é **fortemente recomendado**, pois aumenta produtividade, qualidade e consistência — mas **não é obrigatório**.

---

# 🧠 Princípios

- AI é uma ferramenta para amplificar engenharia
- Clareza > complexidade
- Segurança > velocidade
- Consistência entre serviços é essencial
- Decisão final sempre é humana

---

# 🤖 Uso de AI (recomendado)

Recomendamos o uso de AI nos seguintes cenários:

## 🔹 1. Antes de implementar mudanças relevantes

Use AI para:

- entender o impacto da mudança
- identificar riscos
- validar abordagem

---

## 🔹 2. Durante implementação

Use AI para:

- gerar código base
- sugerir melhorias
- evitar duplicação
- manter consistência

---

## 🔹 3. Após implementação

Use AI para:

- revisar código
- identificar edge cases
- validar integrações
- sugerir melhorias

---

## 🔹 4. Antes de abrir PR

Recomendado:

- revisão com AI
- análise de impacto
- validação de regras do projeto

---

# 🧩 Ferramentas

Você pode utilizar qualquer ferramenta de AI:

- Copilot
- Cursor
- Zed
- Claude Code
- ou outras

👉 Desde que:

- respeite as regras do projeto
- não prejudique o fluxo de trabalho do time
- mantenha consistência com o código existente

---

# 📄 Regras do projeto (obrigatório respeitar)

Independentemente da ferramenta utilizada, é obrigatório seguir:

- `.rules`
- `AGENTS.md`
- `CLAUDE.md`
- `.github/copilot-instructions.md`

Esses arquivos definem como o código deve ser escrito e mantido.

---

# 🧠 Boas práticas com AI

## ✔️ Faça

- Use AI para acelerar tarefas repetitivas
- Use AI para revisar código
- Use AI para entender partes complexas do sistema
- Combine AI com julgamento técnico

## ❌ Evite

- confiar cegamente na AI
- gerar código sem entender
- ignorar padrões do projeto
- introduzir inconsistências

---

# ✅ Checklist antes do PR

Antes de abrir um PR, recomenda-se:

- [ ] Código revisado (com ou sem AI)
- [ ] Consistência com `.rules`
- [ ] Impacto avaliado (outros serviços / módulos)
- [ ] Integrações validadas
- [ ] Edge cases considerados

---

# 🧠 Uso de modelos (referência)

## ⚡ Modelos leves (ex: GPT-5.1-mini)

- autocomplete
- tarefas simples
- código repetitivo

---

## 🧠 Modelos avançados (ex: GPT-5.4, Claude)

- debugging
- decisões técnicas
- análise de impacto
- refatorações

---

# 🔁 Fluxo recomendado

1. Entender o problema
2. (Opcional) Validar com AI
3. Implementar solução
4. Revisar (com ou sem AI)
5. Ajustar
6. Abrir PR

---

# 🧠 Regras críticas

Sempre garantir:

- idempotência em operações críticas
- segurança em retries
- proteção contra race conditions
- consistência de dados
- tratamento seguro de APIs externas

---

# 🧪 Auditoria e evolução

Recomendado:

- rodar auditorias periódicas
- atualizar rules após mudanças relevantes
- revisar padrões do projeto com frequência

---

# 📝 Commits (Commitizen)

Padrões:

```bash id="commit-types"
feat: nova funcionalidade
fix: correção de bug
chore: manutenção
refactor: refatoração
docs: documentação
```

---

## 🤖 Commits relacionados a AI (opcional)

```bash id="commit-ai"
feat(ai): generate rules
chore(ai): update rules
docs(ai): add audit report
refactor(ai): improvements based on AI suggestions
```

---

# 🧠 Filosofia do time

- AI é uma ferramenta, não uma obrigação
- Consistência do código é mais importante que a ferramenta usada
- O time deve conseguir trabalhar junto independentemente da ferramenta escolhida

---

# 🏁 Conclusão

Você é livre para usar AI da forma que preferir.

👉 Desde que:

- respeite as regras do projeto
- mantenha qualidade e consistência
- não impacte negativamente o fluxo do time
