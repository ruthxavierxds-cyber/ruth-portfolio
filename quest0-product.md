# Quest 0 — Ship a $5–29 Digital Product in 7 Days (Gumroad)

> For Ruth. Honest noob framing: you don't need to be an expert. You need one useful artifact, a clear promise, and 7 days of focused work. No API budget, no fake reviews, no hype.

---

## 1. Five Tiny Product Ideas (pick ONE)

All are docs/templates you can build in a weekend. Prices in the $5–29 band.

| # | Idea | Buyer | Why it fits Ruth | Effort |
|---|------|-------|------------------|--------|
| 1 | **Blender Tip Sheet** — 20 shortcuts + 5 render gotchas for beginners | Blender noobs | She uses Blender; pain she already felt | Low |
| 2 | **WSL Setup Checklist** — from zero to working dev env (Ubuntu + Python + ffmpeg) | Windows users learning Linux | Lived experience, bilingual EN/PT | Low |
| 3 | **ffmpeg Command Cheat Sheet** — copy-paste one-liners for creators (trim, concat, subtitles, audio extract, GIF) | YouTubers/editors | High demand, pure reference, no code to debug | Low |
| 4 | **Prompt Template Pack** — 15 reusable prompts for docs/emails/code review | Solo devs/creators | Reuses her own prompts | Low-Med |
| 5 | **Simple Python Automation Template** — a tiny script + README that renames/organizes files | Noob automators | Reuses her automation habit | Med |

### Primary pick (recommended): **#3 — ffmpeg Command Cheat Sheet for Creators**

**Why this one first:** highest search demand, zero runtime risk (it's text), fastest to ship, and every command is verifiable on her own machine. It also feeds later products (bundles with WSL checklist).

---

## 2. MVP Spec — ffmpeg Command Cheat Sheet for Creators

- **Format:** PDF (A4, 8–12 pages) + optional .txt of all commands. No video, no code repo.
- **Title:** "ffmpeg One-Liners for Creators — Copy-Paste Commands That Just Work"
- **Promise:** "Stop Googling ffmpeg. 40 tested commands for trim, concat, subtitles, audio, GIF, and thumbnails. Each with example input/output filenames."
- **Sections:**
  1. Install (Windows/WSL/macOS one line each)
  2. Inspect a file (`ffprobe` one-liners)
  3. Trim / cut (lossless + re-encode)
  4. Concatenate clips
  5. Extract audio / convert formats
  6. Subtitles (burn-in + soft)
  7. Thumbnails & screenshots
  8. GIF (high quality)
  9. Resize / compress for social
  10. Batch loop (bash one-liner)
  11. Troubleshooting table (5 common errors)
- **Each command:** code block + "what it does" + "example" + "gotcha".
- **Languages:** EN primary; PT one-page bonus appendix (bilingual hook for her audience).
- **Price:** $9 (within $5–29).
- **Delivery:** Gumroad PDF download, instant.
- **Out of scope (v1):** no GUI, no scripts, no support beyond email.

---

## 3. 7-Day Day-by-Day Plan

### Day 1 — Validate (2–3 h)
- Search Gumroad/Reddit/X for "ffmpeg cheat sheet" / "ffmpeg commands". Note 3 competitors + their prices.
- Write 5 candidate titles. Pick one promise sentence.
- Post a value-first teaser (see template #1) in 1 community. Goal: ≥3 replies or saves = green light.
- **Gate:** if zero interest after 48h, switch to idea #2 (WSL checklist). Don't ship into silence.

### Day 2 — Outline & Draft (3–4 h)
- Finalize section list (above). Create Notion/Markdown doc.
- Draft all commands from her own terminal history + ffmpeg docs.
- Test every single command on 2 real files (mp4 + mkv). Fix broken ones.

### Day 3 — Polish & PT Appendix (2–3 h)
- Add "gotcha" notes and troubleshooting table.
- Translate 1-page appendix to PT (or at least bilingual tips).
- Add cover page + "how to use" page.

### Day 4 — Package (2 h)
- Export to PDF (LibreOffice/WeasyPrint/pandoc). Check mobile readability.
- Name file: `ffmpeg-one-liners-creators-v1.pdf`.
- Create a .txt companion with raw commands.
- Zip both → `ffmpeg-one-liners-creators.zip`.

### Day 5 — List on Gumroad (1.5 h)
- Create product, upload zip, set price $9.
- Write listing copy (section 4).
- Upload cover image (section 4 spec).
- Set refund policy (section 6).
- Preview as buyer; test download.

### Day 6 — Share / Launch (2 h)
- Post 3 launch posts (section 5) staggered across the day.
- Reply to every comment within 2 h.
- DM 5 friends/creators for honest feedback (not reviews).

### Day 7 — Iterate & Deliver (2 h)
- Collect feedback; fix typos/commands in v1.1.
- Send update to buyers (Gumroad email) — free upgrade.
- Write 3-line "what I learned" note; decide Quest 1.

---

## 4. Gumroad Listing Copy

**Title:** ffmpeg One-Liners for Creators — Copy-Paste Commands That Just Work

**Price:** $9

**Description (paste-ready):**

> Stop Googling the same ffmpeg commands.
>
> This is a short, no-fluff PDF with 40 tested ffmpeg one-liners for creators: trim, concat, subtitles, audio extract, thumbnails, GIFs, and social-ready compression. Every command includes an example filename and a "gotcha" note so you don't waste an hour on a typo.
>
> **What's inside**
> - Install in one line (Windows / WSL / macOS)
> - Inspect any file with ffprobe
> - Trim & cut (lossless + re-encode)
> - Concatenate clips
> - Extract & convert audio
> - Burn-in & soft subtitles
> - Thumbnails & screenshots
> - High-quality GIFs
> - Resize/compress for social
> - One bash loop to batch-process a folder
> - Troubleshooting table (5 common errors)
> - PT appendix (bônus)
>
> **Who it's for:** YouTubers, editors, and automators who use ffmpeg occasionally and forget the flags. Not for ffmpeg experts.
>
> **Format:** PDF + .txt of all commands. Instant download.
>
> **Honest note:** I'm a beginner who got tired of re-Googling. These are the commands I actually use. If something's wrong, email me and I'll fix it in the next update (free for buyers).

**Cover image spec (1200×1200 or 1280×720):**
- Dark background (#0f172a), monospace font.
- Big text: "ffmpeg ONE-LINERS" + "40 tested commands".
- Sub-line: "trim · concat · subs · GIF · audio".
- Small badge bottom: "PT bônus incluído".
- No stock photos of "hackers". Clean terminal aesthetic.
- Tool: Canva free or a single HTML→screenshot. Keep under 1MB.

---

## 5. Launch Post Templates (value-first)

### Template A — Discord (community/help channels)
> Hey folks — I kept re-Googling the same ffmpeg flags, so I wrote them down. Sharing 5 free ones here, full sheet on Gumroad ($9, link in bio/DM).
>
> 1. Trim first 30s lossless: `ffmpeg -ss 0 -t 30 -i in.mp4 -c copy out.mp4`
> 2. Extract audio: `ffmpeg -i in.mp4 -vn -c:a libmp3lame out.mp3`
> 3. GIF high quality: `ffmpeg -i in.mp4 -vf "fps=15,scale=480:-1:flags=lanczos" -c:v gif out.gif`
> 4. Thumbnail at 5s: `ffmpeg -ss 5 -i in.mp4 -frames:v 1 thumb.jpg`
> 5. Concat list: `ffmpeg -f concat -safe 0 -i list.txt -c copy out.mp4`
>
> Happy to answer ffmpeg questions in thread. What command do you always forget?

### Template B — Reddit (r/ffmpeg, r/VideoEditing, r/NewTubers) — value-first, no spam
> Title: "I compiled 40 ffmpeg one-liners I actually use (free samples inside)"
>
> Body: I'm a beginner creator who kept losing 20 min per edit to Googling flags. I wrote down the commands I reuse: trim, concat, subs, audio, GIF, thumbnails, social compression, plus a batch loop and a troubleshooting table.
>
> Free samples (5 commands) — [paste 5]. Full list is $9 on Gumroad (link in comments only if asked). Not selling expertise — selling my notes. Feedback welcome, especially wrong flags.

### Template C — X/Twitter
> I kept re-Googling ffmpeg flags.
>
> So I wrote down the 40 I actually use — trim, concat, subs, audio, GIF, thumbnails, social compression, batch loop, troubleshooting.
>
> 5 free ones 👇
> [thread: one command per tweet, each with gotcha]
> Full sheet: $9 on Gumroad (link in bio). Beginner notes, not expert gospel.

---

## 6. Feedback / Testimonial Request Script

Send 48h after purchase (Gumroad email or DM):

> Hey [name] — thanks for grabbing the sheet. Quick question: did any command not work for you, or anything missing? Reply here and I'll fix it in the next update (free). If it saved you time, a one-line testimonial I can quote (with your handle) would mean a lot. No pressure either way — and if it didn't help, reply and I'll refund, no questions.

Rules: only quote people who opted in. Never fabricate. If 0 testimonials, ship v1.1 with "no reviews yet — early buyers get free updates" honesty.

---

## 7. Honor Rules (non-negotiable)

- **No fake reviews.** No self-reviews, no paid reviews, no "ask a friend to leave 5 stars." Early = honest "no reviews yet."
- **Refund policy:** 14-day no-questions refund (Gumroad supports). State it on listing. Honor it fast.
- **No inflated claims.** "Beginner's notes," not "ultimate guide." No "make $X" promises.
- **Don't buy followers/traffic.** Organic only (budget = $0).
- **Credit sources.** ffmpeg docs + community snippets; link in appendix.
- **Scope honesty.** If a buyer asks for something out of scope, say "not in v1, adding to roadmap."
- **Bilingual honesty.** PT appendix is a bonus, not a full translation — state that.

---

## 8. Success Metrics (Quest 0 done when…)

- [ ] Product live on Gumroad with working download
- [ ] 3 launch posts published
- [ ] ≥1 real buyer OR ≥5 substantive feedback replies
- [ ] v1.1 shipped within 7 days of launch
- [ ] "What I learned" note written (feeds Quest 1)

### If it flops
That's data, not failure. Reuse the same pipeline for idea #2 next week. The asset (workflow, listing template, cover template) is reusable — that's the real win.

---

*Quest 0 — ship small, ship honest, ship again.*