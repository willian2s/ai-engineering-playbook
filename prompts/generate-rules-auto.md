You are a senior software architect and staff-level engineer.

Analyze the current repository and generate a complete AI instruction system for this project.

You must infer everything from the codebase, including:

- architecture patterns
- folder structure
- service boundaries
- naming conventions
- integration patterns
- error handling strategies
- critical business flows

---

# OBJECTIVE

Generate a set of AI instruction files that define how AI agents should behave when working in this repository.

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

- clear and structured
- readable by humans and AI
- includes brief reasoning behind rules
- no fluff

## CLAUDE.md

- similar to AGENTS.md
- slightly more direct and execution-focused
- no unnecessary explanations

## .github/copilot-instructions.md

- shorter version
- focused on coding behavior
- highly practical

---

# WHAT YOU MUST IDENTIFY FROM THE CODEBASE

- architecture style (e.g. layered, modular, etc.)
- patterns in controllers/services/repositories
- integration with external systems
- async flows and event handling
- critical consistency risks
- areas prone to bugs (e.g. payments, concurrency, state sync)

---

# CRITICAL ENGINEERING CONSTRAINTS

You MUST enforce rules that prevent:

- data inconsistency
- race conditions
- duplicated operations (especially in critical flows)
- unsafe retries
- fragile integration handling

---

# STYLE

- no generic advice
- no vague statements
- enforce real engineering constraints
- prioritize production safety over speed
- prefer short and clear rules

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
- Do NOT include analysis
- Output ONLY the files
