# 🤖 AI Engineering Playbook

Este repositório define um sistema estruturado para uso de IA no desenvolvimento de software.

O objetivo é transformar IA em uma ferramenta previsível, consistente e escalável, garantindo qualidade de engenharia e evitando comportamento aleatório.

---

# 🎯 Objetivo

Padronizar:

- como problemas são analisados
- como soluções são planejadas
- como decisões técnicas são tomadas
- como código é implementado
- como escalar o uso de IA com segurança

---

# 🧠 Filosofia

A IA deve operar como um engenheiro sênior que:

- pensa antes de agir
- planeja antes de executar
- trabalha de forma incremental
- valida impacto
- evita complexidade desnecessária

---

# 📁 Estrutura do projeto

```
/ai
  /prompts
    /core
      generate-rules-auto.md
      update-rules.md
      audit-architecture.md
    /planning
      problem-breakdown.md
      execution-planner.md
      validation-planner.md
    /execution
      backend-pattern.md
      frontend-pattern.md
```

---

# ⚙️ Fluxo principal

problem → breakdown → planning → validation → execution → code

---

# 🧠 Etapas do sistema

## 1. Problem Breakdown (opcional)

Usado quando:

- o problema não está claro
- envolve múltiplos sistemas
- existe risco técnico

Resultado:

- entendimento profundo
- identificação de riscos
- levantamento de dependências

---

## 2. Execution Planning (core)

Sempre que possível, use este passo.

Responsável por:

- transformar problema em plano executável
- definir estratégia
- quebrar em etapas pequenas
- reduzir risco

Resultado:

- plano claro e executável

---

## 3. Validation (opcional)

Usado quando:

- a task é crítica
- existe risco de erro
- o fluxo é complexo

Responsável por:

- validar o plano
- identificar falhas e gaps
- detectar riscos reais

Resultado:

- plano seguro para execução

---

## 4. Execution

Responsável por:

- implementar o plano
- manter consistência e simplicidade
- evitar overengineering

---

# ⚖️ Decision Rule

Simples → execução direta

Moderado → execution-planner

Complexo / risco:
→ problem-breakdown
→ execution-planner
→ validation-planner
→ execution

---

# ⚖️ Quick Decision Matrix

| Tipo de tarefa       | Ação            |
| -------------------- | --------------- |
| Ajuste local         | Execução direta |
| Função simples       | Execução direta |
| Refactor pequeno     | Execução direta |
| Debug simples        | Execução direta |
| -------------------- | --------------- |
| Task não trivial     | Planning        |
| -------------------- | --------------- |
| Debug complexo       | Fluxo completo  |
| Multi-arquivo        | Fluxo completo  |
| Integração externa   | Fluxo completo  |
| Lógica crítica       | Fluxo completo  |
| Concorrência / async | Fluxo completo  |

---

# 🚨 Quando escalar

Use fluxo completo quando houver:

- falha repetida
- múltiplos arquivos ou módulos
- integração externa
- lógica crítica
- ambiguidade
- concorrência / async

---

# ⚙️ Execução

## Backend

Foco em:

- consistência de dados
- performance
- segurança
- concorrência e async

---

## Frontend

Foco em:

- estado e renderização
- consistência de UI/UX
- controle de re-render
- tratamento de loading/erro

---

# 🧱 Templates

Use templates quando:

- precisar de maior controle
- garantir padrão
- evitar inconsistência

---

# 🤖 Uso de IA

Fluxo ideal:

1. Entender → breakdown (se necessário)
2. Planejar → execution-planner
3. Validar → (se necessário)
4. Executar → implementação

---

# ⚖️ Regras importantes

- Nunca codar sem entender
- Preferir soluções simples
- Evitar abstrações desnecessárias
- Evitar dependências para problemas triviais
- Fazer mudanças incrementais
- Reutilizar padrões existentes

---

# 💡 Princípio central

IA não substitui engenharia
IA amplifica engenharia

---

# 🏁 Conclusão

Este sistema garante:

- mais previsibilidade
- menos bugs
- menos retrabalho
- decisões mais conscientes
- maior consistência

---

# 🚀 Como começar

1. Pegue uma task
2. Use execution-planner
3. Execute o plano
4. Escale apenas se necessário
