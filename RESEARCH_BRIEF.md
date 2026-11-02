# Market Intelligence Research Brief
## Global AI & Data Talent Market — pay, demand and hiring implications

**Prepared by:** Lisha Bhowmik · **Date:** 2 Nov 2026 · **Built with:** Amazon QuickSuite Market Intelligence Agent (Kaggle dataset + Quick Research)
**Rubric map:** 1 Objective & Scope · 2 Approach · 3 Key Insights · 4 Visual Evidence · 5 Confidence & Limitations · 6 Strategic Implications & Next Steps · 7 Leadership Summary · Appendices

---

## 0. Leadership summary (read this first)

AI-skill demand is growing roughly **8× faster than the overall job market**, and pay is structured mainly by **seniority** (executive ≈ 3× entry-level), then **location** (Switzerland, Norway, Denmark and the US lead) and **company size** (large ≈ +28%). Python and SQL are the most requested skills, but **no individual skill shows a reliable pay premium**. Junior pipelines are under pressure.

**Decision this supports:** how to budget and structure AI/data hiring and pay for 2027.
**How far to trust it:** only the demand-growth signal is High confidence. Everything drawn from the Kaggle data is capped at Medium because the data shows synthetic-data signatures; treat dataset figures as *directional benchmarks to validate*, not as market facts.
**Recommended actions:** (1) stress-test budgets against rising AI-talent costs; (2) build pay bands on level → location → firm size and validate with a real salary survey; (3) invest in Python/SQL fundamentals and internal training rather than tool-specific premiums; (4) close evidence gaps (dataset provenance, named competitors) within one quarter.

---

## 1. Research objective and scope

**Objective.** Determine where pay and demand are concentrated in the global AI/data talent market and what a leadership team planning AI hiring and compensation should conclude.

**Research questions.**
1. How fast is demand for AI skills growing?
2. What drives pay: seniority, location, company size, skills, work model, education?
3. Which skills are most requested, and do they earn a premium?
4. What is happening to entry-level talent supply?

**Scope.**

| In scope | Out of scope |
|---|---|
| 15,000 AI job postings per file, 2 files, Jan 2024–Apr 2025, 20 countries, 20 titles, 15 industries | Named competitor analysis (dataset has only 16 generic company names) |
| External signals 2025–26 (PwC, Lightcast, Stanford AI Index, India reports) | Realised compensation (equity, bonus), forecasts beyond 2026 |

---

## 2. Approach

| Step | What was done | QuickSuite component |
|---|---|---|
| 1. Internal knowledge base | Kaggle dataset (two CSVs, unmodified) uploaded to a Space | Space + agent knowledge source |
| 2. Dataset profiling | Checked structure, duplicates, missing values. **Found the two files share job IDs but are independent samples** (0% matching salaries) → File B = primary, File A = replication check | Agent |
| 3. Internal analysis | Median salary by level, country, title, industry, company size, remote ratio, education; skill frequency; within-level skill premium; monthly postings | Agent |
| 4. External signals | Research objective on demand, pay, skills, work model, entry-level, India; every figure logged with source, date and quality flag (primary / secondary / unverified) | Quick Research |
| 5. Synthesis | Market analysis combining dataset [DS] and external [EXT] evidence | Agent |
| 6. Validation | Each insight re-tested on File A, compared against external sources, rated High / Medium / Low | Agent |
| 7. Leadership brief | This document | Agent |

**Confidence rule.** *High* = replicates in both files **and** corroborated by primary external sources. *Medium* = one of the two. *Low* = neither, or contradicted. Because the data looks synthetic, no dataset-only insight can be High.

---

## 3. Key insights

| # | Insight | Evidence | Why it matters | Confidence |
|---|---|---|---|---|
| **1** | **AI-skill demand is growing ~8× faster than the overall job market.** | [EXT] PwC 2026: jobs requiring AI skills **+69%** vs **+9%** overall (>1 bn ads, 27 countries). Lightcast: AI share of US postings **2.5%**, +55% YoY; agentic-AI postings 0.06% → 0.23%. [DS] Cannot show a trend (postings flat, 842–1,021/month). | Competition for AI talent keeps rising; plans built on 2024 conditions will under-budget. | **High** (direction) / Medium (magnitude) |
| **2** | **Seniority is the biggest pay lever.** Median EN $66k → MI $92k → SE $129k → EX $197k (**2.97×**). | [DS] Same in File A (2.94×); correlation of years of experience with salary r = 0.74 in both. Education and benefits score show no effect. [EXT] none retrieved. | Most pay-budget variance sits in level mix, not in title or industry. | **Medium** |
| **3** | **A stable high-pay tier: Switzerland, Norway, Denmark, US** pay +44% / +33% / +28% / +15% above the overall median. | [DS] All four rank top 4–5 in both files; 11 of 20 countries agree within 10% across files, but **7 differ by >25%** (India $38k vs $76k; China, Japan, Ireland, Austria, Finland, Israel). [EXT] Lightcast ranks countries by AI-skill *share* (Singapore 4.8%, Hong Kong, Luxembourg, Spain, US 2.6%), which is demand, not pay. | Location strategy for senior hires; the dataset cannot be used for emerging-market benchmarks. | **Medium** (top tier) / **Low** (India, China, others) |
| **4** | **Large companies pay ~28% more than small ones; remote status makes no difference to pay.** | [DS] L vs S: +28% in both files; remote 0/50/100%: $106–109k. [EXT] none for size; remote data (65% of AI postings remote) is unverified and contradicts the dataset's 33% split. | Firm size should be a band factor; do not assume a remote discount. | **Low** |
| **5** | **Python (30%) and SQL (23%) are the most-requested skills, but individual skills carry no reliable pay premium.** | [DS] Within-level skill effects −1.4% to +1.7%; ranking does not replicate (ρ = 0.15). [EXT] Lightcast: Python is the #1 specialised AI skill (258,674 US postings, ~+30% YoY). PwC's **62%** AI wage premium is AI vs non-AI work, which the dataset cannot test. | Hire and train for fundamentals; do not pay tool-specific premiums on this evidence. | **Medium** (demand) / **Low** (premium) |
| **6** | **Entry-level pipelines are under pressure.** | [EXT] Stanford AI Index 2026: headcount of software developers aged 22–25 fell 2021–25 while older groups grew; 32% of organisations expect AI to reduce headcount. PwC: AI-exposed entry-level roles are 7× more likely to require senior-type skills. [DS] Not testable. | "Buy" strategies for junior talent may fail; internal training may need to fill the gap. | **Medium** |

---

## 4. Visual evidence

![Salary by level](outputs/charts/05_salary_by_level.png)

**Figure 1: Median salary by experience level (Insight 2)**

![Salary by country](outputs/charts/01_salary_by_country.png)

**Figure 2: Median salary by company location, File B (Insight 3)**

![Replication](outputs/charts/07_replication_country.png)

**Figure 3: The same country medians in two independent files (Insight 3 and reliability).** Top-tier countries match; India, China, Japan, Ireland, Austria, Finland and Israel do not.

![Top skills](outputs/charts/03_top_skills.png)

**Figure 4: Share of postings requiring each skill (Insight 5)**

![Skill premium](outputs/charts/04_skill_premium.png)

**Figure 5: Skill salary premium within seniority level: all effects under ±2% (Insight 5)**

![Trend](outputs/charts/06_postings_trend.png)

**Figure 6: Postings per month are flat, so the dataset cannot show demand growth (Insight 1)**

---

## 5. Confidence and limitations

### 5.1 Insight-level evaluation

| Insight | Supporting evidence | Gaps / assumptions | Confidence | What cannot be concluded |
|---|---|---|---|---|
| 1 Demand growth | Three independent primary sources (PwC, Lightcast, Stanford) agree on direction | Periods and definitions differ; PwC period not stated on page; Lightcast is US-centric | **High** / Medium magnitude | Growth for a specific country or role; growth after 2026 |
| 2 Seniority ladder | Replicates (2.97× vs 2.94×); r = 0.74 | No external benchmark retrieved; synthetic risk | **Medium** | Exact multiples for a real employer or country |
| 3 Country tiers | Top 4 replicate; 7 of 20 countries unstable | Cost of living, tax and FX ignored; fixed FX in the data | **Medium** top / **Low** rest | Rankings below the top tier; India and China salaries |
| 4 Size / remote | Size +28% replicates; remote null replicates | Size not controlled for country or seniority; remote conflicts with external claim; no external source for size | **Low** | Causality; real remote-work pay |
| 5 Skills | Python/SQL frequency replicates and matches Lightcast; no-premium result does not replicate | Skill vocabulary is ~25 tags, with no LLM/agentic skills; dataset has no non-AI comparison | **Medium** / **Low** | Premium for any specific skill, in either direction |
| 6 Entry-level | Stanford and PwC (primary) | Stanford page gave no % figure; PwC is US-only | **Medium** | Size of decline; applicability outside the US |

### 5.2 Cross-checks performed

| Check | Result |
|---|---|
| File overlap | Same 15,000 job IDs, 0% matching salary: independent samples |
| Rank agreement A vs B (country / title / industry / skill premium) | ρ = 0.80 / 0.19 / −0.14 / 0.15: only country (top tier) replicates |
| Category uniformity (coefficient of variation of counts) | 0.02–0.04: implausibly uniform for real postings |
| Implied FX rates (`salary_local / salary_usd`) | Constant for every row (EUR 0.85, GBP 0.75, JPY 110…): synthetic signature |
| External sources | PwC, Lightcast, Stanford read directly; Indeed Hiring Lab not readable; Rework (remote share) has no stated method → treated as unverified |

### 5.3 Key limitations
1. **Likely synthetic data.** Agreement between the two files rules out random noise, not a shared generator.
2. **Posting ≠ pay.** Advertised salary only; no equity or bonus.
3. **Timing mismatch.** Dataset ends Apr 2025; external signals run to 2026.
4. **No real employers** → segment-level, not company-level, competitive view.
5. **Raw medians only.** No significance tests or regression controls.
6. **Quick Research gap.** External evidence must be cross-checked against the saved Quick Research output in the Space.

---

## 6. Strategic implications and recommended next steps

| Implication | Recommended action | Owner / timing |
|---|---|---|
| AI-talent costs will keep rising (Insight 1) | Stress-test 2027 hiring budgets with a demand-growth scenario instead of 2024 pay levels | Finance + HR, next planning cycle |
| Level, location and firm size structure pay (Insights 2–4) | Build pay bands on level → location → firm size; **validate against a real salary survey** (Levels.fyi, Radford, internal HRIS) before adoption | Compensation, within 1 quarter |
| Fundamentals matter more than tools (Insight 5) | Hire and train for Python/SQL; avoid tool-specific premiums until better data exists | Talent acquisition + L&D |
| Junior pipelines are thinning (Insight 6) | Pilot internal early-career training pathways to replace external junior hiring | L&D, pilot within 2 quarters |
| Evidence is not yet decision-grade | Verify dataset provenance; replace with a real posting feed; rerun Quick Research with named competitors and LLM/agentic skill coverage | Analytics, within 1 quarter |

---

## 7. Leadership summary
The leadership summary is Section 0 on page 1, placed first for quick review.

---

## Appendices (supporting files in the repo)

| Appendix | File |
|---|---|
| A. Dataset reference and profile | `docs/01_dataset_profile.md`, `data/*.csv` |
| B. Quick Research objective | `research/quick_research_objective.md` |
| C. External signals log (sources, figures, quality flags) | `research/external_signals.md` |
| D. Full market analysis | `docs/02_market_analysis.md` |
| E. Full reliability evaluation | `docs/03_reliability_evaluation.md` |
| F. Agent configuration and prompts | `agent/agent_config.md` |
| G. Reproducible analysis code and metrics | `analysis/analyze.py`, `outputs/metrics.json` |
| H. QuickSuite runbook and checklist | `docs/05_quicksuite_runbook.md` |

**Sources:** [PwC 2026 Global AI Jobs Barometer](https://pwc.com/gx/en/news-room/press-releases/2026/pwc-2026-ai-jobs-barometer.html) · [Lightcast: Four Takeaways from the 2026 Stanford AI Index](https://lightcast.io/resources/blog/stanford-ai-2026) · [Stanford AI Index 2026, Economy](https://hai.stanford.edu/ai-index/2026-ai-index-report/economy) · [Business Today, 12 Jun 2026](https://www.businesstoday.in/technology/artificial-intelligence/story/indias-ai-talent-can-earn-rs60-lakh-a-year-heres-which-skills-pay-the-most-536404-2026-06-12) · [PropertyCasualty360 on Indeed Hiring Lab](https://www.propertycasualty360.com/amp/2026/05/04/hiring-demand-for-ai-skills-outpaces-candidate-interest/) · [Rework (unverified)](https://resources.rework.com/news/ai-jobs-skills/remote-ai-roles-talent-geography-shift)
