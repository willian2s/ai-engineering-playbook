You are a senior software architect.

Based on the provided project context, generate a complete AI instruction system for this repository.

---

# OBJECTIVE

Generate AI rules that define how agents should behave when working in this project.

---

# FILES TO GENERATE

1. `.rules`
2. `AGENTS.md`
3. `CLAUDE.md`
4. `.github/copilot-instructions.md`

---

# REQUIREMENTS

## .rules

- concise, strict, dense
- bullet points only
- no explanations
- optimized for LLM automatic ingestion
- max ~120 lines

## AGENTS.md

- structured and readable
- includes reasoning
- no unnecessary verbosity

## CLAUDE.md

- direct and execution-focused
- similar to AGENTS.md but slightly stricter

## .github/copilot-instructions.md

- short and practical
- focused on coding behavior

---

# MUST INCLUDE

- Project context (stack, architecture)
- Critical rules (business-critical constraints)
- Architecture guidelines
- Coding standards
- Integration rules
- Debugging approach
- Monorepo/service boundaries (if applicable)
- Final guiding principle

---

# CRITICAL RULES TO ENFORCE

- idempotency in critical operations
- safe retry mechanisms
- protection against race conditions
- consistency across services
- safe handling of external APIs

---

# STYLE

- no generic advice
- no vague statements
- prioritize real-world engineering constraints
- focus on safety and maintainability

---

# OUTPUT FORMAT (STRICT)

Return EXACTLY:

--- FILE: .rules ---
<content>

--- FILE: AGENTS.md ---
<content>

--- FILE: CLAUDE.md ---
<content>

--- FILE: .github/copilot-instructions.md ---
<content>

---

# IMPORTANT

- Do NOT explain anything
- Do NOT add commentary
- Output ONLY the files

---

# PROJECT CONTEXT

[COLE AQUI DESCRIÇÃO DO PROJETO, ARQUIVOS, OU TRECHOS]
