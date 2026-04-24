# 🤖 AI Engineering System

Este diretório define como a IA é utilizada no projeto.

O objetivo é manter o uso de IA:

- simples
- consistente
- previsível

---

# 🧠 Princípio central

> Um único source of truth: AGENTS.md

- Todas as regras ficam no AGENTS.md
- Não duplicar regras em prompts
- Não criar variações por ferramenta

---

# 📁 Estrutura

.ai/

core/ → geração e atualização de rules
tasks/ → execução de tarefas

---

# 🤖 AGENTS.md

Define o comportamento dos agents:

- arquitetura
- padrões de código
- boas práticas
- regras de execução
- uso de dependências

👉 É a base de tudo

---

# ⚙️ CORE

Responsável por gerar e manter o AGENTS.md.

Inclui prompts como:

- generate-rules → cria regras com base no projeto
- update-rules → mantém regras atualizadas

---

# 🎯 TASKS

A pasta `tasks/` contém prompts de execução.

Cada task:

- recebe uma descrição
- segue o AGENTS.md
- gera código diretamente

---

## 📄 Exemplo

Arquivo: `tasks/EXAMPLE.md`

    # 🎯 EXECUTION AGENT

    You are a senior software engineer.

    Your role is to implement the requested task following AGENTS.md.

    ---

    ## 🎯 TASK

    [DESCREVA A TASK]

---

# ⚙️ Fluxo padrão

task → execução → código

---

# ⚡ Uso no dia a dia

1. Descreva a task
2. Use um prompt da pasta `tasks/`
3. Revise o código gerado
4. Ajuste se necessário

---

# 🧠 Quando pensar mais antes

Use análise adicional apenas quando necessário:

- problema não está claro
- envolve múltiplos sistemas
- existe risco de dados
- fluxo é crítico

👉 nesses casos, pense antes de executar

---

# 🧠 Princípios de engenharia

- Preferir simplicidade
- Evitar abstrações desnecessárias
- Evitar dependências para problemas triviais
- Reutilizar antes de criar
- Fazer mudanças incrementais
- Seguir AGENTS.md sempre

---

# 🚀 Boas práticas

- Revisar sempre o código gerado
- Não confiar cegamente na IA
- Manter consistência com o projeto
- Usar IA como apoio, não substituição

---

# 🏁 Conclusão

Sistema intencionalmente simples:

- AGENTS.md define as regras
- core mantém as regras
- tasks executam

---

## Resultado esperado

- mais velocidade
- menos retrabalho
- código consistente
- uso eficiente de IA
