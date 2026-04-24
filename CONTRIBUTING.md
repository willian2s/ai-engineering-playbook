# 🤝 Contributing Guide

Este projeto adota uma abordagem de **AI-assisted engineering**.

O uso de Inteligência Artificial é recomendado para aumentar produtividade, qualidade e consistência — mas não é obrigatório.

---

# 🧠 Princípios

- AI amplifica engenharia, não substitui
- Clareza > complexidade
- Segurança > velocidade
- Consistência é obrigatória
- Decisão final é sempre humana

---

# ⚙️ Fluxo de desenvolvimento

Todo desenvolvimento deve seguir, sempre que possível, o fluxo:

problem → breakdown → planning → validation → execution → code

---

## ⚖️ Regra de decisão

Simples → execução direta

Moderado → execution-planner

Complexo / risco:
→ problem-breakdown
→ execution-planner
→ validation-planner
→ execução

---

## 🚨 Quando escalar

Use o fluxo completo quando houver:

- falha repetida
- múltiplos arquivos ou módulos
- integração externa
- lógica crítica
- ambiguidade
- concorrência / async

---

# 🤖 Uso de AI

A AI pode ser utilizada em qualquer etapa do fluxo.

---

## 🔹 Antes de implementar

Use para:

- entender o problema
- identificar riscos
- estruturar abordagem (planning)

---

## 🔹 Durante implementação

Use para:

- gerar código base
- reduzir repetição
- manter consistência
- seguir padrões existentes

---

## 🔹 Após implementação

Use para:

- revisar código
- identificar edge cases
- validar integrações
- melhorar qualidade

---

## 🔹 Antes do PR

Recomendado:

- revisar código
- validar impacto
- garantir consistência com o projeto

---

# 📄 Regras do projeto

Todo código deve seguir:

- padrões existentes no projeto
- boas práticas de arquitetura
- consistência entre módulos

Evitar:

- duplicação
- abstrações desnecessárias
- dependências para problemas triviais

---

# 🧠 Boas práticas com AI

## ✔️ Faça

- Use AI para acelerar tarefas repetitivas
- Use AI para estruturar soluções
- Use AI para revisar código
- Combine AI com julgamento técnico

---

## ❌ Evite

- confiar cegamente na AI
- gerar código sem entender
- ignorar padrões do projeto
- introduzir inconsistência

---

# ⚙️ Execução

## Backend

Garantir:

- consistência de dados
- tratamento de erros
- segurança
- idempotência quando necessário

---

## Frontend

Garantir:

- consistência de estado
- controle de renderização
- tratamento de loading/erro
- experiência do usuário

---

# ✅ Checklist antes do PR

- [ ] Código revisado
- [ ] Consistência com o projeto
- [ ] Impacto avaliado
- [ ] Integrações validadas
- [ ] Edge cases considerados

---

# 🧠 Regras críticas

Sempre garantir:

- idempotência em operações críticas
- segurança em retries
- proteção contra race conditions
- consistência de dados
- tratamento seguro de integrações externas

---

# 📝 Commits

Padrões:

feat: nova funcionalidade
fix: correção de bug
chore: manutenção
refactor: refatoração
docs: documentação

---

# 🧠 Filosofia do time

- AI é uma ferramenta, não uma obrigação
- O processo é mais importante que a ferramenta
- Consistência do código é essencial
- O time deve conseguir trabalhar junto independentemente da ferramenta

---

# 🏁 Conclusão

Você é livre para usar AI da forma que preferir.

Desde que:

- respeite o fluxo do projeto
- mantenha qualidade e consistência
- não introduza riscos desnecessários
