# Tasks workflow

Operational guidelines for this project. Use this folder to plan work, track lessons, and keep context clear.

## Files

| File | Purpose |
|------|--------|
| [to-do.md](to-do.md) | Plan and track current work. Checkable items, progress notes, review section. |
| [lessons.md](lessons.md) | Patterns and rules from user corrections. Update after any correction; review at session start. |

## Workflow

1. **Plan first** – Write the plan in `to-do.md` with checkable items.
2. **Verify plan** – Confirm the plan is correct and complete before starting implementation.
3. **Track progress** – Mark items complete in `to-do.md` as you go; add a short summary at each step.
4. **Review** – After implementation, fill in the "Review / rationale" section. Ask: would a staff engineer approve?
5. **Lessons** – After any user correction, add an entry to `lessons.md` so the same mistake is not repeated.

## Principles

- **Verification before done** – Never mark a task complete without proving it works (build, tests, quick check).
- **Elegance** – For non-trivial changes, pause and ask if there is a more elegant way; don't over-engineer simple fixes.
- **Bug fixing** – Fix from logs, errors, and failing tests; fix failing CI without extra hand-holding.
- **Subagents** – Offload research, exploration, or parallel analysis to keep main context focused.
