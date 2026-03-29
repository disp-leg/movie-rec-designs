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

## Progress — COMPLETE

All 11 design options built and pushed to GitHub Pages: https://disp-leg.github.io/movie-rec-designs/

| # | Aesthetic | Fonts | Palette | Key Feature |
|---|-----------|-------|---------|-------------|
| 1 | Editorial Magazine | Playfair Display + Inter | Off-white, charcoal, burgundy | Parallax hero, pull quotes, bookmark micro-interaction |
| 2 | Brutalist | Space Mono + Inter | Black, white, red only | Ticker tape, glitch hover, step-start timing |
| 3 | Glassmorphism (Warm) | DM Sans | Forest green, cream/rose glass | Frosted panels, floating particles, parallax orbs |
| 4 | Retro Analog/VHS | Press Start 2P + VT323 | Phosphor green, amber, charcoal | CRT boot sequence, scan lines, typed text reveal |
| 5 | Swiss Minimalist | Inter | Black, white, Swiss red | Visible grid, sticky headers, sort/filter controls |
| 6 | Japanese Zen | Cormorant Garamond + Inter | Stone, moss, clay, paper | Extreme whitespace, drifting petals, ink-fade animations |
| 7 | Editucation.io Clone | Inter + Plus Jakarta Sans | Dark + red accent | Exact branding match, Framer-style sections, FAQ accordion |
| 8 | Warm Bento Grid | Plus Jakarta Sans | Sage, cream, rose, stone | Varied tile sizes, staggered reveals, pill navigation |
| 9 | Cinematic Full-Bleed | Bebas Neue + Inter | Deep blacks, color grading | Scroll-snap full-viewport, letterboxing, progress dots |
| 10 | Vinyl Record | Space Grotesk + DM Sans | Cream, brown, dusty gold | Spinning discs, crate browsing, sleeve pull-outs |
| 11 | Film Strip/Reel | Courier Prime + Inter | Amber celluloid, dark leader | Sprocket holes, contact sheets, projector flicker |

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
