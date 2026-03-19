# Behavior
- Always ask if unclear or unsure about any decision.
- In all interactions, plans, and commit messages, be extremely concise and sacrifice grammar for the sake of concision.
- Always respond in Russian.
- Development documentation under `docs/**` must be written in Russian.
- All rules, agent instructions, and skills must be written in English.
- Never include large logs in context without explicit user approval; use only minimal, targeted excerpts.

# Bugs
- add regression test when it fits.

# Tests
- Don't write tests for what the type system already guarantees

# Token Efficiency
- Never re-read files you just wrote or edited. You know the contents.
- Never re-run commands to "verify" unless the outcome was uncertain.
- Don't echo back large blocks of code or file contents unless asked.
- Batch related edits into single operations. Don't make 5 edits when 1 handles it.
- Skip confirmations like "I'll continue..."  Lust do it.
- If a task needs 1 tool call, don't use 3. Plan before acting.
- Do not summarize what you just did unless the result is ambiguous or you need additional input.