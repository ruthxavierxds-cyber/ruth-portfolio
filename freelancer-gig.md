# Freelancer Gig Package — Ruth (early-career, honest framing)

> Ready-to-paste package for Fiverr/Upwork. Frame: **fast, reliable, ethical delivery**. Early-career is stated openly — no fake reviews, no invented clients. Placeholders in `[brackets]`.

---

## 0. Positioning (use everywhere)

- **Who:** Ruth — creative technologist, bilingual EN/PT, Python/ffmpeg/Blender/WSL.
- **Stage:** early-career, learning by shipping. Say it plainly; buyers who want cheap-and-fast + clear communication love this.
- **Promise:** scoped deliverable in <1 day, plain-English/PT updates, clean handoff (code + README + how-to-run).
- **Never:** fake reviews, plagiarized samples, overpromising, "passive income" hype, or accepting work you can't finish in scope.

---

## 1. Three <1-day gig ideas

| # | Gig | Deliverable | Time | Tools | Buyer |
|---|-----|-------------|------|-------|-------|
| 1 | **Spreadsheet / CSV cleanup & organization** | Dedupe, fix columns, split/merge, basic formulas, export clean XLSX/CSV + short note of changes | ≤1 day (≤5k rows) | Python (pandas) / LibreOffice | Anyone with messy data, small biz, researchers |
| 2 | **Simple Python automation script** (PRIMARY) | One scoped script that automates one repetitive task + README + example run | ≤1 day | Python 3, stdlib-first | Creators, small biz, devs wanting a quick helper |
| 3 | **Basic graphic / banner** | 2 concepts + 1 final in requested sizes (social, YouTube thumb, site banner) | ≤1 day | Canva / Inkscape / ffmpeg | Creators, small biz, event promos |

**Pick ONE to launch first.** Recommendation: start with #1 (spreadsheet cleanup) for first 3–5 reviews (lowest risk, highest volume), then add #2 as the "hero" gig. #3 only if you enjoy design.

---

## 2. PRIMARY GIG — full copy: "Simple Python Automation Script"

### 2.1 Title (pick one, ≤80 chars)

- `I will write a simple Python automation script to save you time`
- `I will automate one repetitive task with a clean Python script`
- `I will build a small Python script to automate your workflow`

### 2.2 Category / subcategory

- Fiverr: Programming & Tech → Python (or "Automation")
- Upwork: Web, Mobile & Software Dev → Python / Automation

### 2.3 Description (paste as-is, fill brackets)

```
Hi! I'm Ruth — an early-career creative technologist (bilingual EN/PT) who
ships small, focused tools fast. I'll write ONE clean Python script that
automates a single repetitive task you describe, with a README so you can run
it yourself.

WHAT I CAN DO (examples):
- Rename/move/organize files in bulk (by pattern, date, extension)
- Clean or transform a CSV/Excel file (dedupe, split columns, reformat)
- Batch-convert or resize images, or generate simple reports
- Scrape a single public page into CSV/JSON (respecting robots.txt)
- Glue two tools together (e.g., read a folder → produce a summary)
- Small CLI helpers with flags and clear output

WHAT YOU GET:
- A single, readable Python 3 script (stdlib-first; dependencies only if needed, listed)
- A short README: how to install, run, and customize
- One example run on sample data you provide
- Clear limits stated up front — no scope creep

WHAT I WON'T DO (ethical limits):
- No scraping behind logins/paywalls or ignoring robots.txt
- No malware, spam, or account-automation that violates a site's ToS
- No "AI magic" claims — I build small, honest tools

PROCESS:
1. You describe the task + share sample input (sanitized; remove secrets).
2. I confirm scope and edge cases in messages before coding.
3. I deliver code + README + example output.
4. One round of revisions within the original scope.

I'm early in my freelance journey, so I over-communicate and under-promise. If your
task is bigger than one script, I'll say so and propose a split — no surprises.
```

### 2.4 Packages

| Package | Price | Name | What's included | Delivery |
|---------|-------|------|-----------------|----------|
| Basic | **$15** | Quick Script | 1 simple script (≤60 lines), stdlib only, README, 1 example run | 1 day |
| Standard | **$35** | Script + Polish | Up to ~150 lines, optional 1–2 pip deps, CLI flags, README, example run, 1 revision | 1 day |
| Premium | **$75** | Script + Support | Up to ~300 lines, deps, CLI flags, README, simple tests, 2 revisions, 7 days of email support for tweaks | 2 days |

Notes:
- "Lines" are a guide, not a contract. Scope by **one task**, not lines.
- Premium "support" = small tweaks/questions, not new features.
- If a job needs >1 script or a web app, quote separately (don't force into a tier).

### 2.5 Tags (Fiverr: 5 tags)

`python` · `automation` · `script` · `csv` · `workflow`

Alternates if taken: `python script`, `file automation`, `data cleaning`, `cli tool`.

### 2.6 FAQ (paste into gig FAQ)

**Q: I don't know Python. Can I still use this?**
A: Yes. I deliver a README with copy-paste commands. If you can open a terminal, you can run it. I can also record a 2-min Loom showing how.

**Q: Can you scrape any website?**
A: Only public pages that allow it (robots.txt + ToS). I'll check before starting and tell you if it's not allowed.

**Q: What if my task is bigger than one script?**
A: I'll say so up front and propose splitting into multiple gigs or a custom quote. No hidden upsells.

**Q: Do you use AI to write the code?**
A: I use AI assistants as a tool (like a calculator) and I review/test everything before delivery. You get working, readable code I can explain line by line.

**Q: What's your experience level?**
A: Early-career. I'm honest about that. I compensate with fast turnaround, clear communication, and scoped work I can actually finish. If something's beyond me, I'll refer you elsewhere.

**Q: Revisions?**
A: Basic: bug fixes only. Standard: 1 revision within scope. Premium: 2 revisions within scope. New features = new gig.

### 2.7 Requirements from buyer (Fiverr "Requirements" section)

Ask the buyer to provide:
1. **Task in one sentence** (what the script should do, start → end).
2. **Sample input** (sanitized file or 5–10 example rows; remove passwords/PII).
3. **Expected output** (what "done" looks like — filename, format, columns).
4. **Environment** (OS: Windows/Mac/Linux; Python version if known; can they run a terminal?).
5. **Edge cases** they know about (empty files, weird characters, duplicates).
6. **Deadline** and timezone.
7. Confirmation they own the data / have rights to process it.

Refuse to start until #1–#3 are answered. (Prevents 90% of disputes.)

---

## 3. Delivery workflow checklist (use per order)

**Intake (before coding)**
- [ ] Restate task in 2–3 lines; get buyer "yes, that's it"
- [ ] List assumptions + edge cases; get confirmation
- [ ] Confirm scope fits the tier; upsell/redirect if not
- [ ] Get sanitized sample input (no secrets/PII)

**Build**
- [ ] Write script with clear functions + docstrings
- [ ] Use stdlib first; add deps only if needed (pin versions)
- [ ] Add `--help`, sensible defaults, error messages
- [ ] Handle empty/bad input gracefully (no silent failures)
- [ ] Run on buyer's sample; capture example output

**Handoff**
- [ ] `script.py` + `README.md` + `example_input/` + `example_output/`
- [ ] README: install, run, customize, limits, troubleshooting
- [ ] Zip or GitHub link; deliver on Fiverr/Upwork
- [ ] Send a 2–3 line summary of what it does + how to run

**After delivery**
- [ ] Ask for feedback (script below) within 24h of delivery
- [ ] Log: hours spent, revenue, hourly rate, what went wrong
- [ ] If < $20/hr effective → tighten scope or raise price next time

---

## 4. Review-request script

Send **after** buyer confirms it works (not before). EN + PT.

**English (Fiverr message):**
```
Hey [name] — glad the script is working for you! 🎉

If this saved you time, a quick review would mean a lot for an early-career
freelancer like me (it's how I get found). Even a one-line review helps.

No pressure at all — and if anything's off, tell me first and I'll fix it
before you review. Thank you for trusting me with this!

— Ruth
```

**Português:**
```
Oi [nome] — que bom que o script funcionou! 🎉

Se isso te economizou tempo, uma avaliação rápida faria muita diferença pra
mim (freelancer em início de carreira — é assim que apareço nas buscas).
Mesmo uma linha já ajuda.

Sem pressão — e se algo não estiver certo, me avisa antes e eu corrijo.
Obrigada por confiar em mim!

— Ruth
```

Rules:
- Ask only after confirmed working.
- Never offer discounts/gifts in exchange for reviews (ToS violation).
- If buyer is unhappy, fix first; ask for review only after resolved.

---

## 5. Price-raise trigger (after 10 five-star reviews)

**Trigger:** 10 completed orders with 5★ reviews (and ≤1 revision request per order).

**Action (in order):**
1. **Basic $15 → $20**, Standard $35 → $45, Premium $75 → $95.
2. Add a "Rush delivery (24h)" extra at +$10.
3. Update gig description: add "10+ 5★ reviews" line + 1–2 real (buyer-quoted) testimonial snippets (with permission).
4. Re-evaluate after next 10 reviews: if effective hourly ≥ $30, raise again; if < $20, tighten scope instead of raising.

**Guardrails:**
- Never raise before 10 real 5★ reviews. No fake reviews, no "review swaps."
- Keep a log: date, review count, new prices, reason.
- If a price raise kills orders for 14 days, revert one tier and revisit scope.

---

## 6. 7-day launch plan

| Day | Action | Done? |
|-----|--------|-------|
| 1 | Create Fiverr + Upwork accounts (use real name, photo, bilingual profile). Set up 2FA. | ☐ |
| 2 | Build **portfolio samples**: 3 mini scripts (file renamer, CSV cleaner, folder→ZIP) in a public GitHub repo with READMEs. No client data. | ☐ |
| 3 | Publish PRIMARY gig (Python script) with copy above. Add 3 gig images (simple, clean, Canva). | ☐ |
| 4 | Publish SECONDARY gig (spreadsheet cleanup) with shorter copy. | ☐ |
| 5 | Set daily routine: check messages 2x/day, reply within 4h, deliver early. Send 5 polite "buyer request" bids on Upwork (honest, small scope). | ☐ |
| 6 | Deliver first order (even if $15) with full checklist. Ask for review using script. | ☐ |
| 7 | Review metrics: orders, hours, $/hr, messages. Adjust tags/title. Write 1 troubleshooting writeup for portfolio. | ☐ |

**Daily habits after launch:**
- Reply within 4 hours (even "got it, starting tomorrow").
- Deliver 1 day early when possible.
- Keep a `gig-log.md`: date, gig, price, hours, $/hr, notes.
- One improvement per week (image, FAQ, tag).

---

## 7. Ethics & safety guardrails

- No scraping behind auth/paywalls; respect robots.txt + ToS.
- Never handle buyer secrets in plain text; ask them to sanitize.
- No fake reviews, no review swaps, no bought engagement.
- Decline work you can't finish in scope; refund promptly if you can't deliver.
- Keep client data confidential; delete after delivery unless agreed otherwise.
- Honest about AI use: disclose if asked; always review/test output.

---

## 8. Quick tracking template

```
Date | Gig | Tier | Price | Hours | $/hr | Review? | Notes
-----|-----|------|-------|-------|------|---------|------
```

**Kill rule:** if a gig averages < $20/hr after 5 orders, tighten scope or drop it.

---

*Built for Ruth — honest, fast, ethical. Update as you learn.*
