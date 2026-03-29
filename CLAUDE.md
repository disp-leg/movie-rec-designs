# Web App Project — MSAP Node

@~/.claude/docs/node-operating.md

---

## Project Context

This is a web application project node. All operator communication goes through Yuna (hub) via your liaison agent. Do NOT access Telegram directly.

## Stack Preferences
- Node.js / Express or Next.js depending on scope
- Vanilla HTML/CSS/JS for simple projects, React for complex
- SQLite for local data, Postgres for production
- Dark theme by default

## Workflow
1. Initialize project structure and git
2. Build core functionality first — no premature abstraction
3. Test as you go
4. Commit at logical checkpoints with clear messages
5. When done: run pre-graduation self-review, update lessons, then signal completion

## Agents Available
- test-runner (haiku) — run tests after each feature
- code-reviewer (sonnet) — review before major commits
- frontend-specialist (opus) — complex UI work

When spawning agent teams for short tasks (<15 min), include the content of `~/.claude/docs/agent-team-briefing.md` in their instructions.

## Completion Criteria
- App runs locally without errors
- Core features working as specified
- Clean git history
- Pre-graduation self-review completed
- Lessons learned documented
- Deliverable statement written

---

## Assumptions

- [VERIFIED] TMDB poster URLs are accessible without API key for direct image links
- [VERIFIED] GitHub Pages is live at https://disp-leg.github.io/movie-rec-designs/
- [VERIFIED] editucation.io is a Framer site using SF Pro Display + Plus Jakarta Sans fonts
- [UNVERIFIED] All 20 TMDB poster paths resolve correctly (agents have onerror fallbacks to Amazon images)

## Progress

### Tranche 1+2 Status (Options 1-6)
- **Option 1** (Editorial Magazine) — DONE, pushed. Playfair Display + Inter, burgundy accent, parallax hero.
- **Option 2** (Brutalist) — DONE, pushed. Space Mono, black/white/red, ticker tape, glitch effects.
- **Option 3** (Glassmorphism) — IN PROGRESS (designer-alpha-3)
- **Option 4** (Retro Analog/VHS) — DONE, pushed. Press Start 2P + VT323, CRT scan lines, tracking bars.
- **Option 5** (Swiss Minimalist) — DONE, pushed. Inter, grid-obsessed, Swiss red accent, scroll progress.
- **Option 6** (Japanese Zen) — IN PROGRESS (designer-alpha-2)

### Remaining (Options 7-11)
- Option 7: Editucation.io clone — queued
- Option 8: Warm Bento Grid — queued
- Option 9: Cinematic Full-Bleed — queued
- Option 10: Vinyl Record Metaphor — queued
- Option 11: Film Strip/Reel — queued

## Approval Scope

**You decide (Level 1 — no approval needed):**
- Implementation approach (which pattern, which library, file structure)
- Code architecture within project scope
- Test strategy
- Bug fix approach for bugs in the project
- Refactoring within scope
- Order of operations within the approved plan
- Edge case handling
- How to structure your own agent teams

**Escalate to your liaison (Level 2):**
- Requests for additional agents from hub roster
- Model tier changes for agents
- Scope changes extending timeline by >25%
- Decisions needing other projects' state or global memory
- Resource contention
- Significant plan deviations

**Escalate to Yuna/operators (Level 3 — via liaison):**
- Anything affecting node existence (completion, abort)
- Changes affecting other projects or operators
- Cross-node coordination

## Pre-Graduation Self-Review

- [ ] Re-read the original task direction. Does the deliverable match what was asked?
- [ ] Does the code compile/build without errors?
- [ ] Were all tests run and passing?
- [ ] Are there any hardcoded values, TODOs, or placeholder code?
- [ ] Is the `## Assumptions` section up to date?
- [ ] Are lessons learned documented in `## Lessons Learned`?
- [ ] Is the deliverable statement written in `## Deliverable`?

## Lessons Learned

## Deliverable
