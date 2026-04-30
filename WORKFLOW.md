# 🧠 AI Workflow Cheat Sheet (Zed + OpenCode Go + Codex)

## ✍️ Edit Prediction (inline)

- GitHub Copilot ou Zed nativo
  → Autocomplete, sugestões rápidas
  → Não envolve OpenCode nem Codex

---

## 🤖 Zed Agent (OpenCode Go)

### 🟢 Default (80% dos casos)

- DeepSeek V4 Flash
  → Gerar código, CRUD, ajustes, leitura de arquivos

---

### 🟡 Quando resposta ficar fraca

- Qwen3.5 Plus
  → Melhor coerência, refactor leve

---

### 🟠 Debug / lógica mais complexa

- Kimi K2.5
  → Múltiplos arquivos, bugs difíceis

---

## 🧠 Codex (ACP)

### 🔵 Default Codex

- GPT-5.3-Codex
  → Refactor grande, execução de tasks, code review

---

### 🟣 Pensamento mais profundo

- GPT-5.4
  → Arquitetura, decisões, AGENTS.md

---

### 🔴 Casos extremos

- GPT-5.5
  → Problemas muito complexos

---

## 📝 Commits

### 🟢 Default

- DeepSeek V4 Flash
  → Commits rápidos, Conventional Commits, diffs simples

---

### 🟡 Quando diff for maior

- Qwen3.5 Plus
  → Melhor descrição, múltiplas mudanças

---

### 🔵 Commits complexos

- GPT-5.3-Codex
  → Refactors grandes, impacto em vários arquivos

---

## 🔁 Fluxo mental

Flash → Qwen → Kimi → Codex → GPT-5.4

---

## 🏁 TL;DR

- Rápido/barato → Flash
- Melhorar resposta → Qwen
- Debug pesado → Kimi
- Executar de verdade → Codex
- Pensar/arquitetura → GPT-5.4
- Commits → Flash (default)
