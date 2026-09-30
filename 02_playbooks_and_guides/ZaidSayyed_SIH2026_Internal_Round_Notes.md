# SIH 2026 College Internal Round Playbook — Notes

> **Source:** <https://zaidsayyed.in/blog/sih-2026-internal-hackathon-guide>
> **Title:** *Smart India Hackathon (SIH) 2026: College Internal Round Playbook*
> **Author:** Zaid Sayyed
> **Published:** 27 Aug 2026 · 1 min read
> **Scraped:** 2026-09-30
>
> Companion to: [Winners Playbook Notes](./ZaidSayyed_SIH2026_Winners_Playbook_Notes.md)

## TL;DR / Core Insight

Over **60% of teams** get eliminated at the College Internal Hackathon round. The college SPOC has a hard ceiling of **max 45 teams (30 Software + 15 Hardware)** nominated to AICTE. If 150 teams apply on campus, 100+ are eliminated here — the round deciding it **never sees your code, your demo, or your team**.

Key numbers: **45 max** campus nominations · **30+15** software+hardware · **3 mins** jury pitch · **10 secs** live mockup hack.

---

## TOPIC 01 — How to Clear the College Internal Round (Top-45 Cutoff Strategy)

### The 45-Team AICTE Limit
Each college SPOC may nominate a max of **45 teams (30 Software + 15 Hardware)**. 150 applicants → 100+ eliminated.

### Faculty Psychology: What Professors Grade vs. What Gets Disqualified

**❌ Disqualification traps:**
- Walls of text copied from Wikipedia or ChatGPT
- Promising AI + Blockchain + IoT all together in 36 hours
- 1 person talking while 5 teammates stand silent
- Arguing defensively when a professor raises a doubt

**✅ Top-45 winner formula:**
- **10-second clickable mobile UI mockup** (v0.dev / Figma)
- Clean **system architecture diagram** with clear data flow
- Clear role split — each teammate answers their own domain
- Respectful acknowledgment: **"Great point sir, incorporated in Phase 2."**

### The 7-Day Action Plan
> *"Round wale din faculty aapko pehli baar na dekhe."* (Don't let the faculty see you for the first time on the day.)

- **Day 7–5 · SPOC & Faculty Mapping:** Confirm the exact submission deadline + evaluation criteria from the college SPOC; identify which senior professors will be on the judging panel.
- **Day 4–3 · The Pre-Round Cabin Visit (the secret weapon):** Visit professors' cabins: *"Sir, hum Ministry of Agriculture ke is PS par kaam kar rahe hain, aapka 2-minute architectural feedback chahiye."* Get them mentally invested in your project before they evaluate it.
- **Day 2 · 10-Second Clickable Mobile Prototype:** Build 3 core UI screens as an interactive clickable prototype on v0.dev or Figma; verify the link opens offline on mobile.
- **Day 1 · 3-Minute Pitch Stopwatch Rehearsal:** 30s Problem Context + 60s Live UI Mockup + 30s 36-Hour Feasibility + 60s Q&A Defense. Run the stopwatch, practice 3 times.
- **Day 0 (Hackathon) · Zero-Panic Campus Selection:** The jury won't be seeing you for the first time. Show, don't just speak — lock the Top-45 nomination.

### Interactive Faculty Viva Defense Sheet — The 3 Deadliest Professor Questions

**Q1 — Market Exist:** *"Market mein already Google/Startup ka solution exist karta hai, tumhara kyun lein?"*
- ⚠️ Trap: *"Hamara app better UI aur free hai."* (rejected immediately)
- 🎯 Script: *"Sir, existing consumer apps urban English users ke liye hain aur high-speed internet maangte hain. Hamara system ministry-specific compliance follow karta hai, offline-first, local bhasha mein chalta hai, aur official government server APIs se real-time sync karta hai jo kisi private commercial tool ke paas nahi hai."*
- Senior tip: always lead with **Ministry Compliance, Offline-first, and Local Language**.

**Q2 — 36h Feasibility** (implies): use the modular 12/14/10 hour-split answer (see TOPIC 05).

**Q3 — Ministry Data** (implies): name real sources — data.gov.in, ministry reports, Bhuvan for geospatial (see TOPIC 05).

### Campus Readiness Audit — 5-Point Pre-Submission Compliance Checklist
- ✅ Team structure: exactly **6 members with 1+ female** confirmed
- ✅ SPOC registration: college SPOC verified & active on **sih.gov.in** portal
- ✅ Clean architecture diagram created on **Eraser.io / Draw.io**
- ✅ 10-sec live mockup: **3 clickable screens** ready on mobile (v0.dev / Figma)
- ✅ Offline backup: PPT & recorded screen demo on a **pen drive** (zero Wi-Fi reliance)
- *Copy master checklist into the team WhatsApp group.*

---

## TOPIC 02 — Everything to Do Before You Walk In

> "I know your project is not finished. Nobody's is, and that is not what you lose on. Spend the last night on being ready rather than one more feature."

- **Be honest about the statement:** a statement can look like a perfect fit and still need a skill your team lacks. Use the free matcher (checks all 240 against your team) to surface the gap.
- **Get one screen working, then stop coding:** the one screen that shows what the project actually does; fake all the data. A feature added the night before is the one that breaks in the room.
- **Record the demo and write one page:** recording saved on laptop + phone (downloaded, not Drive); one page on who has this problem — a real person, what they do today, what it costs them.
- **Say your first 90 seconds out loud, standing, twice:** reading in your head doesn't count. Say it aloud and you'll find 2–3 lines you can't actually say.
- **Pack the bag tonight:** laptop + charger charged (sockets are never where you need them); backup video on two devices; slides as PDF on a pen drive AND emailed to yourself (fonts break on other machines); one named person carries all of it — *"I thought you had it"* is a real way to lose.
- **Five minutes outside the room:** decide who speaks (one person) and split questions by area — one owns data/domain, one owns how it's built, one owns impact. Do it out loud.

---

## TOPIC 03 — Backup Plans: Eight Things That Break, and What Covers Each

> Almost none of this is about your project.

1. **College Wi-Fi will let you down** (30 teams + 100 phones). Have two teammates keep a hotspot ready; connect your laptop to one beforehand so nobody types a password while a jury watches.
2. **Never demo an empty dashboard.** Seed it — data.gov.in has thousands of government datasets, the statement's ministry publishes reports, Kaggle has something close to any domain.
3. **Have the demo on video, offline.** If the live demo dies: don't freeze, don't debug — say *"let me show you the recorded run"* and keep talking. Juries don't mind; what they mind is not seeing it work at all.
4. **Assume the laptop won't be yours.** PDF on a pen drive; project pushed to GitHub so it can be pulled onto any machine in five minutes.
5. **Run it locally too.** If the demo needs a hosted link, it needs the internet — and you've already assumed the internet fails.
6. **A second person should know the opening.** People freeze; people get stuck in traffic. One more person should be able to deliver the first 90 seconds cold.
7. **Agree what you say when you don't know.** Don't guess (juries tell instantly). One person says *"we haven't tested that yet, here's how we'd approach it"* and gives two sentences on the approach.
8. **Know which three slides matter.** You may get stopped at minute four; most teams race through everything. Decide in advance the three you'd want them to have seen — usually problem, demo, and the impact number.

---

## TOPIC 04 — In the Room: The Eight Minutes, and the Questions After

> The order matters more than the content. Everyone rehearses 15 minutes; almost nobody gets 15. Faculty have 30 teams in an afternoon and are tired by the tenth. You get ~8 minutes, and their real attention is in the **first 90 seconds**.

- **0:00–2:00 · The problem, why nobody solved it.** Not the statement read aloud. One real person, what they do today, what it costs them. Name the actual blocker: no connectivity, no incentive, too expensive, nobody owns the data. These two minutes buy the other six.
- **2:00–4:00 · The demo, before the architecture.** Two full minutes. Narrate as you click; don't apologise for what's missing. If you only get through half your slides, this is the half that must survive.
- **4:00–6:30 · How it works, then one number.** Architecture now — one diagram, three or four boxes. Then a single figure they could write down. Not five metrics (teams that list five give the jury nothing to remember).

**Use your hands:** When a question comes, whoever owns that area raises a hand and answers; everyone else stays quiet. Never let two people answer one question — the second voice makes the first answer sound incomplete even when it was fine.

**The three you will definitely get:**
- *"Who actually has this problem today?"* → name a real person, don't read the statement back.
- *"What have you built so far?"* → show it; plans are free.
- *"Why this team?"* → six people saying they're all good at coding is worse than four who each name a different job.

**Everyone prepares a slide anyway** — even though only one of you presents. Not to show it, but so everybody knows the whole project. Teams that fall apart in Q&A are the ones where each person only knew their own part.

---

## TOPIC 05 — 18 Questions a Jury Might Ask (trap answer, then the one that works)

> Almost none are technical. Read out loud with your team the night before.

1. **"Who actually faces this problem today?"** — Trap: reading the PS back. Works: name one real person/role, what they do instead now, what it costs in time/money/errors.
2. **"This already exists. Why yours?"** — Trap: "our UI is better and ours is free." Works: theirs is a consumer product; yours is built for the ministry — offline-first, local language, synced with official government data. A private app can't do that.
3. **"Then why has nobody solved it yet?"** — Trap: silence or "nobody thought of it." Works: name the actual blocker (no connectivity, no user incentive, nobody owns the data). You only know this if you read the ministry's report.
4. **"Can you really build this in 36 hours?"** — Trap: promising AI + blockchain + IoT together. Works: a modular plan with hours attached — core prototype in 12, integration in the next 14, testing in the last 10. Say what already works today.
5. **"Where will the data come from?"** — Trap: "we'll use dummy data." Works: name a real source (data.gov.in, ministry reports, Bhuvan for geospatial). If restricted, say you generated a realistic schema modelled on the official format.
6. **"What happens when your model is wrong?"** — Trap: claiming it won't be. Works: say what a false positive and a false negative each cost here + what the system does (human check, confidence threshold, fallback). Knowing your failure mode reads as maturity.
7. **"Why this team?"** — Trap: "we are all good at coding." Works: four people who each name a different job beat six who all do the same one. The jury is estimating whether you survive 36 hours together.
8. **"What will you NOT build?"** — Trap: saying you'll build everything in the statement. Works: name what's out of scope + why. Teams that draw a boundary look like they've planned; teams that promise everything look like they haven't started.
9. **"How does this scale beyond your pilot?"** — Trap: "it's on the cloud so it scales." Works: the non-technical scaling — who onboards the next district, what training is needed, what breaks when language/terrain changes.
10. **"Who pays for this after the hackathon?"** — Trap: "it's free." Works: name the owner (usually the raising department, sometimes an existing scheme budget). Even a rough answer beats none.
11. **"What if the user has no smartphone?"** — Trap: assuming everyone has one. Works: SMS, IVR in the local language, a shared device at the panchayat, a village-level operator. For most rural statements this single answer separates you from the room.
12. **"How is this different from what the ministry already does?"** — Trap: not knowing. Works: name the current process and where it breaks (reactive, paper-based, delayed) and what yours changes specifically.
13. **"What is your accuracy?"** — Trap: a number you can't defend. Works: what it is on your test set, on how many samples, where it fails. An honest 82% with a known weakness beats an unverifiable 99%.
14. **"Show me the hardest part of this."** — Trap: showing the login page/dashboard. Works: know in advance the genuinely difficult part and go straight to it. Tests whether you built it or assembled it.
15. **"What did you build and what did you use?"** — Trap: implying you built everything from scratch. Works: be straight — pretrained model fine-tuned on your data; this API for maps, this one for messaging. Using tools isn't a weakness; pretending you didn't is.
16. **"What happens if the internet goes down?"** — Trap: not having thought about it. Works: offline-first storage that syncs when the connection returns. For rural/disaster statements this is the normal condition, not an edge case.
17. **"Who maintains this after you graduate?"** — Trap: "we'll keep working on it." Works: documentation, a public repo, a handover path to the department or the next batch.
18. **"Give me one number that proves the impact."** — Trap: listing five metrics. Works: one figure they could write down — *"cuts the reporting delay from three weeks to a day."*

> Bottom line: ~5 teams per statement go forward nationally — 5 out of 500 on a filled statement — and **the deciding round reads six slides and nothing else**.

---

## Related Links (from page)

- Back to SIH Master Hub: <https://zaidsayyed.in/blog/sih-2026>
- PS survival sheet (Topmate, paid): <https://zaidsayyed.in/go/sheet>
- 1:1 Team Strategy Call (Topmate): practice your 3-minute college pitch & viva defense
- Next: [The Free Stack: Every Tool You Need to Build an SIH 2026 Prototype](https://zaidsayyed.in/blog/sih-2026-free-stack)