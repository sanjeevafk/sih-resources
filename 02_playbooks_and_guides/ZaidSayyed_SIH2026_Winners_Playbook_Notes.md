# SIH 2026 Winners Playbook — Notes

> **Source:** <https://zaidsayyed.in/blog/sih-2026>
> **Title:** *Smart India Hackathon (SIH) 2026: Winner's Playbook*
> **Author:** Zaid Sayyed (SIH winner, Software Engineer)
> **Published:** 22 Aug 2026 · 5 min read
> **Scraped:** 2026-09-30
>
> Companion post: [College Internal Round Playbook Notes](./ZaidSayyed_SIH2026_Internal_Round_Notes.md)

## TL;DR / Core Insight

Over 80% of teams get eliminated **before writing a single line of code** — mostly by missing college SPOC dates, picking the wrong 6-person team, or selecting dead problem statements.

Key stats bandied on the page:
- ₹1,50,000 prize per problem (see the more detailed prize answers below)
- 6 members per team
- 45 teams per college ceiling
- 36-hour Grand Finale hack

---

## THEMES ROADMAP (10 Topics)

### TOPIC 01 — Tournament Funnel & SPOC Gateway
How college SPOC nomination, campus internal rounds, and national screening work.

### TOPIC 02 — Building the 6-Person Dream Team
Role distribution for 2026 AI problems, avoiding the **6-coder trap**, and 24h teammate vetting.

### TOPIC 03 — Problem Statement Selection Strategy
Optional AICTE evaluation rubric, avoiding dead PS, and a **6-point viability calculator**.

### TOPIC 04 — The 3-W Solution Architecture Blueprint
Deconstructing ministry problems into **Who, What, Outcome** without falling into the Feature Trap.

### TOPIC 05 — The Top 10+ Free Developer Tools Vault
Curated free tools for System Architecture diagrams, instant UI scaffolding, official datasets, and grand finale backups.

### TOPIC 06 — College Internal Hackathon & Top-45 Cutoff Strategy
The 45-team AICTE quota math, faculty vs jury psychology, 7-day action plan, 10-second live mockup hack, and viva defense sheet.
> Detailed breakdown lives in the [companion internal-round notes](./ZaidSayyed_SIH2026_Internal_Round_Notes.md).

### TOPIC 07 — 16 Jury Questions (screening + grand finale)
> *"Almost none of these are technical."* Internal jury = faculty deciding nomination. Screening/finale jury = ministry officer + industry evaluator deciding deployability. **Read these out loud with your team.**

1. **"Walk me through what changed since we last saw you."**
   - Trap: Repeating the same pitch you gave 4 hours ago.
   - Works: Evaluators visit the same table 3–4 times across 36 hours and compare against their own last note. Show the **delta** — what was broken last visit, what works now.
2. **"Show me this running. Not the slides."**
   - Trap: Opening the PPT from slide one.
   - Works: Demo first, 60 seconds, on the thing that actually works. Slides only if asked. At the finale everyone has a deck and few have something running.
3. **"Which of our existing systems would this have to talk to?"**
   - Trap: Not knowing the department already runs software.
   - Works: Name their actual portal/database then how you'd connect (REST, nightly CSV export, whatever is realistic). Even naming the system correctly puts you ahead.
4. **"What is the smallest version we could deploy next month?"**
   - Trap: Describing the full vision again.
   - Works: Name a **pilot with a boundary** — one district, one depot, one crop, fifty users. Officials are costing a pilot, not a platform.
5. **"Who inside the ministry owns this on day one?"**
   - Trap: "The government" / "the ministry."
   - Works: Name the department that raised the statement + the day-to-day role (block officer, depot supervisor, district nodal officer). Ownership kills real projects.
6. **"What law or policy does this have to comply with?"**
   - Trap: Never having thought about it.
   - Works: Name one that genuinely applies + what you did (DPDP Act if personal data; sector rules if health/finance).
7. **"Where does the data sit, and who can see it?"**
   - Trap: "It's on the cloud."
   - Works: Region, access model, what's anonymised. Government data usually cannot leave India.
8. **"What does this cost to run for a year at state scale?"**
   - Trap: "Cloud is cheap" or a bare number.
   - Works: A rough figure with the biggest line item named (inference, storage, SMS). Being roughly right with visible reasoning beats a confident number you can't break down.
9. **"You have not spoken yet. What did you build?"**
   - Trap: The team leader answering on their behalf.
   - Works: Finale juries split teams on purpose. Every member should explain their own module and the one next to it. One person answering = one person did everything.
10. **"Twelve other teams picked this statement. Why yours?"**
    - Trap: Listing features.
    - Works: Name the single thing only you did — usually a constraint others ignored (works offline, runs on a 4-year-old phone, local language).
11. **"This works on your laptop. What breaks in the field?"**
    - Trap: "Nothing, it's production ready."
    - Works: Name three real failures + what you do about each (bad network, no GPS, garbage input). Nobody believes a 36-hour build is bulletproof.
12. **"How long does it take one worker to learn this?"**
    - Trap: "It's intuitive, anyone can use it."
    - Works: A number + assumptions (10 min if they can read the local language, an afternoon if training needed). Adoption is where government software dies.
13. **"What did you get wrong and change during these 36 hours?"**
    - Trap: "Nothing, it went exactly to plan."
    - Works: One real pivot + what triggered it (model too slow → cached; API down → switched sources).
14. **"Open the code for the feature you just showed me."**
    - Trap: Hunting through folders while they watch.
    - Works: Repo open in a second window, know where things live. Not about code quality — a check that the demo is connected to something.
15. **"How much of this is from an existing open source project?"**
    - Trap: Saying none of it.
    - Works: Name what you used, the licence, and what you actually wrote. Being caught overstating is fatal; using a library never is.
16. **"If we gave you three months and a budget, what would you fix first?"**
    - Trap: "Add more features."
    - Works: Name the weakest part of your own system honestly. It's a **maturity test**.

### TOPIC 08 — 10 Questions Nobody Prepares For (sideways, after the demo)
> Every one has a trap answer that *sounds* confident — usually a version of "everything is fine." Say these out loud until the second answer is the reflex.

1. **"How much of this did AI write?"**
   - Trap: "We wrote everything ourselves."
   - Works: Say it plainly — this part is a pretrained model, this is an API, this logic we wrote. Nobody is against AI in 2026, they're against being lied to.
2. **"This is a wrapper on somebody else's API. What is actually yours?"**
   - Trap: Getting defensive, or citing the UI as the contribution.
   - Works: Agree with the premise, then name the part that took real work (routing logic, domain rules, offline fallback, dataset you cleaned).
3. **"What is your accuracy, and how did you measure it?"**
   - Trap: A round number with no test set behind it.
   - Works: Number + size of set + where it fails. *"About 87% on 400 samples, and it drops on night images."* A modest defendable number survives; a 99% claim invites one counter-example.
4. **"Show me your data. Where did it come from?"**
   - Trap: "We used dummy data."
   - Works: Name real sources — data.gov.in, ministry reports, Bhuvan for geospatial. If access needs clearance, say you modelled a realistic set on the official schema and show the schema. The word **dummy** ends discussion.
5. **"We tried something like this before and it did not work. Why is yours different?"**
   - Trap: Assuming they're wrong / nothing existed before.
   - Works: Ask what failed, then answer that specific failure. Usually it was **adoption**, not technology.
6. **"Who runs this after you graduate?"**
   - Trap: "We will maintain it."
   - Works: Documented setup, standard stack their vendor can pick up, open source under a permissive licence, handover docs. Sustainability is scored more often than expected.
7. **"Half the people who need this do not have a smartphone. Now what?"**
   - Trap: "They can use the website."
   - Works: SMS/IVR path, shared operator device at the block office, paper form somebody enters. Gov statements almost always carry a last-mile problem.
8. **"How would somebody cheat this?"**
   - Trap: "They would not, it is secure."
   - Works: Name a real abuse case + your check (fake subsidy entries, one person marking attendance for six, photo from a different location).
9. **"Who pays for this once the pilot money is over?"**
   - Trap: Subscriptions/paying users for a government system.
   - Works: A departmental budget line, made small. Say what one district costs/year + what the department stops paying (manual survey/inspection time). **Cost saved is the language of that room.**
10. **"Explain it to me as if I am the person who has to use it, not a judge."**
    - Trap: Repeating the pitch with the same technical words.
    - Works: Drop every acronym, describe one person's day: *"The inspector opens the app at the site, takes one photo, and the report reaches the district office before he leaves."*

### TOPIC 09 — The Idea Submission Deck, Slide by Slide (6 slides)
> Screening = **reading, not watching.** No jury, no demo, no chance to explain. ~5 teams per statement go forward — on a filled statement that's 5 out of 500, decided by six slides.

1. **Title page** — read for metadata vs the portal's record.
   - Trap: Template text left in (`TO BE UPDATED`, `IDEA TITLE`), theme typed from memory. A wrong theme on slide 1 is the cheapest mark you'll lose.
   - Works: Copy ID, title, theme, category character-by-character from the statement page.
2. **Proposed solution** — read for whether you understood *this* statement.
   - Trap: A description true even if you swap state/ministry/domain ("Unified platform combining AI and data").
   - Works: Name the specific condition that made the ministry raise this (one monsoon, one district with a single road in, one crop, one queue). Test: swap the place name — if the slide still reads fine, it's not about your statement.
3. **Technical approach** — read for whether a real system exists.
   - Trap: A stack of HTML/CSS/JS + a box labelled "AI/ML layer."
   - Works: Name what you actually run — the model, the library, the database, the routing engine. A boring defensible stack beats an impressive uncheckable one.
4. **Feasibility and viability** — read for whether you know where your idea is weak.
   - Trap: Listing only reasons it will work (no risks reads as no thought past the demo).
   - Works: Three real risks + what you do about each (data you can't get, accuracy drops, adoption). This slide separates two decks with the same idea.
5. **Impact and benefits** — read for whether the benefit is measurable.
   - Trap: "Better, faster, improved, enhanced" boxes.
   - Works: One number with your working shown (hours saved/inspection, ₹/district/year, km of road covered).
6. **Research and references** — read for whether your data plan is real.
   - Trap: Entries that name nothing; framework docs counted as research; notes left printed on the slide.
   - Works: Named sources with links (data.gov.in, Bhuvan, ministry annual report, the raising department). If access needs permission, say so + what you use meanwhile.

**8 real mistakes found in 2026 decks this season:**
1. Placeholder text on slides (`TO BE UPDATED`, `IDEA TITLE`, `YOUR TEAM NAME`)
2. Theme on slide 1 that doesn't match the portal's theme
3. A slide belonging to a different project (pasted by an AI tool that misread the idea name)
4. A duplicated slide (deck runs 7 pages where template gives 6)
5. A visible note to self ("verify these references before submission")
6. A title box running off the slide, cutting the first word in half
7. A full map of India used on a statement about one region
8. A live demo on a free host that sleeps → blank page for the first opener

### TOPIC 10 — 3 Free Winning SIH 2025 PPTs
> Why only three: "a folder of 300 winner decks teaches nothing." **All three take the feasibility/viability slide seriously — almost no losing deck does.**

| # | PS ID | Theme | Title | Team | Takeaway | Local copy |
|---|---|---|---|---|---|---|
| 1 | SIH25070 | Miscellaneous · Software | Secure Data Wiping for Trustworthy IT Asset Recycling | Team Niet - SafeSecure | Every risk sits next to its own mitigation; naming your weakness makes the rest believable | `03_winning_presentations_reference/ZaidSayyed_SIH25_PPT1_TeamSafeSecure_DataWiping.pdf` |
| 2 | SIH25175 | Space Technology · Software | MAITRI: An AI Assistant for the Well-Being of Astronauts | Team Zillion Minds | A "What ifs" failure block (AI misreads emotion, hardware dies mid-mission, astronaut refuses) | `03_winning_presentations_reference/ZaidSayyed_SIH25_PPT2_ZillionMinds_MAITRI.pdf` |
| 3 | SIH25071 | Disaster Management · Software | AI-Based Rockfall Prediction and Alert System for Open-Pit Mines | Team TechPioneers | Splits feasibility into technical/economic/operational + lists unsolved problems + a business model — most adaptable | `03_winning_presentations_reference/ZaidSayyed_SIH25_PPT3_TechPioneers_Rockfall.pdf` |

Online sources: `sih-winning-ppt-1.pdf`, `sih-winning-ppt-2.pdf`, `sih-winning-ppt-3.pdf` on `zaidsayyed.in/sih/`.

---

## QUESTIONS I ACTUALLY GET ASKED (recurring Q&A)

**"I'm a first year with no coding background. Can I still do SIH? Can I use AI to build the prototype?"**
Yes to both — using AI is **not cheating**; most teams in 2026 are. Juries ask whether it works and whether you understand the problem. The real risk for a first year is getting cut from the team before SIH starts (seniors form teams quickly; the first dropped is "the one who will learn later"). Don't try to become a competitive coder in 3 weeks. Own a job nobody volunteers for:
- **Domain research** — read the full statement, find ministry reports, know why the problem exists
- **Documentation and slides** — teams with working code still get rejected here
- **Demo operator** — make sure it runs on the day; teams lose rounds to laptops, not logic

Timeless opening move: pick 3 statements, read them fully, write one page per statement on **who suffers from that problem today** — show it to any team you approach.

**"How many teams does my college send forward?"**
Ceiling = **45 nominations (30 software + 15 hardware)**; most colleges don't fill it. Mid-size college reality ≈ 40 teams register, ~half submit, a handful go forward. The internal round is the steepest cut and happens before SIH has technically begun.

**"Should we pick a hardware or a software statement?"**
Hardware has a smaller field (sometimes an advantage) but is unforgiving: can't fake a sensor at 3am, component delivery times, a prototype that doesn't work has nowhere to hide. Pick hardware **only if someone has built with the components before** — "we'll learn Arduino" is not a plan.

**"Everyone is picking the popular statements. Should I avoid them?"**
Partly. Easy-looking statements draw the biggest field (least differentiation). But don't swing to impossible-empty either. The real filter: **can your specific team ship a convincing version in 36 hours?** Use the problem-statement matcher to score statements against your team's actual skills and reveal the missing skill.

Theme crowd-sizes mentioned: smart automation ~55, blockchain & cybersecurity ~31, agriculture/foodtech/rural ~27, disaster management ~25, MedTech/BioTech/HealthTech ~20; quieter ones (space tech, robotics & drones, transport & logistics, clean & green tech) are overlooked for that reason.

---

## WHERE YOU ARE IN THE TIMELINE (phases)

1. **Team formation** — 6 members, real constraints; sort before you fall in love with a statement
2. **Problem statement selection** — longest tail; get it wrong and everything after is harder
3. **College internal round** — the steepest cut (see companion notes)
4. **Screening & submission** — prep stops being about code
5. **Grand finale** — 36 hours; by then the outcome is mostly already decided

> If reading during internals, skip ahead to the internal-round playbook.

---

## THE QUESTIONS EVERYONE ASKS (facts/answers on the page)

- **Prize money:** Each winning team gets ₹1,00,000 per PS at national level; popular editions have carried ₹1,50,000 for some categories. One winner per PS (some declare joint winners). The win isn't about the cheque — it's the credential + people you meet.
- **Last date for SIH 2026 idea submission:** **30 September 2026** (portal). Team leader has the portal login, but the team must be nominated by the college SPOC through the internal hackathon first — so your **real deadline is your college's internal one**, usually 2–3 weeks earlier (internals run through September).
- **Team size:** Exactly **six**, including leader, **≥1 female**, all from the same college (can be different departments). Teams of 4–5 aren't accepted nationally even if your college allows smaller. May add up to **2 mentors with 5+ years' experience**.
- **First years?** Yes — best move available; biggest risk is being dropped from a team before it starts.
- **Software vs hardware:** 2026 has **182 software + 58 hardware** statements.
- **What is a SPOC?** Single Point of Contact — a faculty member your college nominates to manage SIH participation. Registers institution, runs internal hackathon, nominates teams. Crucial: find out who yours is — no submission counts without going through them.
- **Is the internal hackathon compulsory?** Yes. Only teams selected through the institution's internal hackathon can be nominated. Up to 45 teams (30 SW + 15 HW), mostly unfilled.
- **How many teams reach the Grand Finale?** Roughly **5 per problem statement** nationally; on a popular statement that's 500→5, decided entirely by the idea PPT.
- **What actually happens at the Grand Finale?** 36 continuous hours at a nodal centre (usually another city); evaluators visit 3–4 times comparing against their own prior notes → **visible progress between rounds** matters, not one polished demo.
- **Can we use AI tools / pretrained models?** Yes, most teams do. Juries ask what you built and what you used and can tell. Say it straight: pretrained model fine-tuned on our data, this API for maps, this part we wrote. Hiding it is the weakness.
- **Where do we get datasets?** Some statements ship a dataset link, most don't. Name real sources (data.gov.in, ministry reports, Bhuvan for geospatial). If live access needs permission, say you generated a realistic dataset modelled on the official schema. "Dummy data" ends the conversation.
- **Is SIH worth it?** For the win, odds are long. For everything else it's the highest-leverage thing an Indian engineering student can do in a month — a real build under deadline, presenting to professional evaluators, a national cohort. Even internal-round losers get a project, a team, a story that survives interviews.
- **After you win?** Prize + certificate arrive, then nothing compounds unless you build on it — write about it, mentor teams, speak, ship the project further. The win opens doors; it doesn't walk you through them.
- **What does the jury ask?** Far fewer technical questions than expected. College internal = faculty pushing scope, effort split, demo realism. Screening/finale = ministry officer + industry evaluator asking who owns this on day one, where data sits, yearly cost, what breaks in the field, how much AI wrote, who maintains it after graduation. They test **deployability**, not code cleverness.
- **How is the idea PPT evaluated?** By reading, not watching. Six slides survive alone. Evaluators scan for problem understanding, specific (not generic) approach, feasibility showing real constraints instead of promises. A technically stronger team often loses to a clearer deck.
- **How many slides is the idea submission PPT?** **Six** — title page, proposed solution, technical approach, feasibility & viability, impact & benefits, research & references. Format is fixed; going over invites a formatting objection. If a section spills to a 7th slide, **cut, don't add**. Check your deck against the template via the problem-statement tool.
- **Most common PPT mistakes?** Unglamorous: placeholder text; theme mismatch on slide 1; duplicated slide; visible note to self; references name no actual source; demo link on a sleeping free host.
- **How is SIH 2026 different?** 240 PS across **17 themes**, strong AI/automation tilt, visible increase from state governments and PSUs (not just central ministries). Statements are still being added through September. Evaluators now expect you to be explicit about which parts are AI-assisted.

---

## Key Stats Reference

| Item | Value |
|---|---|
| Prize | ₹1,00,000–1,50,000 per problem statement |
| Team | 6 members (≥1 female, same college) + up to 2 mentors |
| College nomination ceiling | 45 (30 software + 15 hardware) |
| PS count 2026 | 240 across 17 themes (182 software + 58 hardware) |
| Finale shortlist | ~5 teams per statement |
| Portal deadline | 30 September 2026 |
| Grand finale | 36 continuous hours, nodal centre |

---

## Related Links (from page)

- Author site: <https://zaidsayyed.in>
- Tools / PS matcher: <https://zaidsayyed.in/tools/sih-problem-statements>
- PS survival sheet (Topmate, paid): <https://zaidsayyed.in/go/sheet>
- Related: [Method overloading vs overriding in Java](https://zaidsayyed.in/blog/method-overloading-vs-overriding-java)
- Next: [College Internal Round Playbook](https://zaidsayyed.in/blog/sih-2026-internal-hackathon-guide)