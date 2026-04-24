# 📄 AI Engineering System

Este diretório contém o sistema completo de engenharia assistida por IA do projeto.

Ele padroniza como problemas são:

- entendidos
- planejados
- validados
- implementados
- evoluídos

---

# 🧠 Princípio central

> Um único source of truth: AGENTS.md

- Todas as regras de comportamento dos agents ficam centralizadas
- NÃO usar múltiplos arquivos de rules
- NÃO duplicar instruções entre ferramentas

---

# 🧩 Arquitetura do sistema

O fluxo segue uma separação clara de responsabilidades:

problem → breakdown → planning → validation → execution → code

---

# 🧠 Etapas do sistema

## 1. 🧠 Problem Breakdown

Objetivo: entender profundamente o problema

Responsável por:

- separar problema vs sintoma
- identificar complexidade oculta
- mapear dependências
- levantar riscos e unknowns

Quando usar:

- problema não está claro
- múltiplos sistemas envolvidos
- risco de dados ou concorrência
- ambiguidade

---

## 2. ⚙️ Execution Planning

Objetivo: transformar o problema em plano executável

Responsável por:

- definir estratégia
- quebrar em etapas pequenas
- minimizar impacto
- evitar overengineering

Quando usar:

- problema já entendido
- pronto para estruturar execução

---

## 3. 🔍 Validation

Objetivo: validar criticamente o plano antes de executar

Responsável por:

- encontrar falhas e gaps
- detectar riscos reais
- questionar decisões implícitas
- evitar erro em produção

Quando usar:

- task crítica
- impacto em dados
- fluxo complexo
- dúvida sobre segurança

---

## 4. 🎯 Execution

Objetivo: implementar com segurança e consistência

Responsável por:

- seguir plano estritamente
- aplicar boas práticas
- evitar abstrações desnecessárias
- manter consistência com AGENTS.md

---

## 5. 🤖 AGENTS.md

Objetivo: garantir comportamento consistente dos agents

Define:

- padrões de código
- arquitetura
- regras de execução
- controle de dependências
- boas práticas gerais

---

## 6. 🔥 Architecture Audit

Objetivo: avaliar a qualidade do sistema

Analisa:

- estrutura
- acoplamento
- complexidade
- redundância
- escalabilidade

---

# ⚙️ Fluxos práticos

## Fluxo simples (80%)

execution-planner → execution → code

---

## Fluxo completo (20%)

problem-breakdown
→ execution-planner
→ validation-planner
→ execution
→ code

---

# ⚖️ Regra de decisão

Simples → execution-planner + execution

Complexo ou arriscado:
→ problem-breakdown
→ execution-planner
→ validation-planner
→ execution

---

# 🚨 Quando usar fluxo completo

- impacto em dados
- múltiplos serviços
- lógica crítica
- concorrência / async
- mudanças estruturais

---

# 🧠 Princípios de engenharia

- Não codar sem entender o problema
- Validar antes de executar quando houver risco
- Preferir soluções simples
- Evitar abstrações desnecessárias
- Evitar dependências para problemas triviais
- Reutilizar antes de criar
- Fazer mudanças incrementais

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

# 🔧 Gestão de regras

generate-rules:

- cria AGENTS.md baseado no projeto

update-rules:

- mantém AGENTS.md atualizado com a evolução do sistema

---

# 🚀 Boas práticas

- revisar outputs antes de aplicar
- versionar mudanças relevantes
- manter prompts alinhados com o projeto
- usar IA como apoio, não substituição de decisão

---

# 🏁 Conclusão

Este não é apenas um conjunto de prompts.

É um sistema de engenharia assistida por IA que garante:

- previsibilidade
- consistência
- qualidade de código
- redução de bugs
- menos retrabalho

---

## Resultado esperado

- código mais limpo
- decisões mais conscientes
- execução mais segura
- uso eficiente de IA no dia a dia
