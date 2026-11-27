---
title: "BEACON: Shining a light on exercise oncology research"
subtitle: "BEACON series, post 1: introducing BEACON and the BEACON Blog"
summary: "Exercise oncology has shown its potential. Its future now depends less on producing more research than on producing better research. An introduction to BEACON and the BEACON Blog, with interactive tasks on research waste and proportionate claims."
authors:
  - admin
tags:
  - exercise oncology
  - research methods
  - research waste
  - clinical trials
  - good clinical practice
  - patient and public involvement
categories:
  - BEACON
  - the BEACON Blog
date: 2026-12-01
lastmod: 2026-12-01
featured: false
draft: false
image:
  caption: "A lighthouse beam shines across the words 'the BEACON Blog: shining a light on exercise oncology research'. Original illustration by Edward N. Stanhope for BEACON."
  focal_point: ""
  preview_only: false
projects: []
---

<!-- BEACON series, post 1. Links to BEACON Background and Chapter 1. Requires markup.goldmark.renderer.unsafe: true in the site config so the HTML components and script render. -->

<style>
.beacon{--b-navy:#1F3A5F;--b-teal:#1D7A74;--b-amber:#C9821B;--b-good:#2E7D4F;--b-poor:#B23A3A;--b-bg:#F5F7FA;--b-line:#D9DEE5;--b-text:#1E2430;font-family:inherit;color:var(--b-text);line-height:1.6;max-width:760px;margin:0 auto}
.beacon *{box-sizing:border-box}
.beacon .b-box{background:var(--b-bg);border:1px solid var(--b-line);border-left:6px solid var(--b-teal);border-radius:8px;padding:1rem 1.25rem;margin:1.75rem 0}
.beacon .b-label{display:inline-block;font-size:.75rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;color:#fff;background:var(--b-teal);border-radius:4px;padding:.15rem .5rem;margin-bottom:.5rem}
.beacon .b-box h3{margin:.25rem 0 .75rem;font-size:1.15rem;color:var(--b-navy)}
.beacon details{background:#fff;border:1px solid var(--b-line);border-radius:6px;margin:.5rem 0;padding:0}
.beacon summary{cursor:pointer;padding:.65rem .9rem;font-weight:600;list-style-position:inside}
.beacon summary:focus-visible{outline:3px solid var(--b-amber);outline-offset:2px}
.beacon details[open] summary{border-bottom:1px solid var(--b-line)}
.beacon details > div{padding:.75rem .9rem}
.beacon .b-correct{color:var(--b-good);font-weight:700}
.beacon .b-incorrect{color:var(--b-poor);font-weight:700}
.beacon .b-takeaway{border-left-color:var(--b-amber)}
.beacon .b-takeaway .b-label{background:var(--b-amber)}
.beacon .b-takeaway p{font-size:1.1rem;font-weight:600;margin:0;color:var(--b-navy)}
.beacon .b-compare{display:grid;grid-template-columns:1fr 1fr;gap:1rem}
@media (max-width:600px){.beacon .b-compare{grid-template-columns:1fr}}
.beacon .b-card{background:#fff;border:1px solid var(--b-line);border-top:6px solid;border-radius:6px;padding:.9rem 1rem}
.beacon .b-card.good{border-top-color:var(--b-good)}
.beacon .b-card.poor{border-top-color:var(--b-poor)}
.beacon .b-card h4{margin:0 0 .5rem;font-size:1rem}
.beacon .b-card.good h4{color:var(--b-good)}
.beacon .b-card.poor h4{color:var(--b-poor)}
.beacon .b-scenario{background:#fff;border:1px dashed var(--b-navy);border-radius:6px;padding:.75rem 1rem;margin-bottom:.75rem;font-style:italic}
.beacon .b-note{font-size:.85rem;color:#555;margin:.5rem 0 0}
.beacon figure{margin:1.75rem 0}
.beacon figure img,.beacon figure svg{width:100%;height:auto;display:block;border-radius:6px}
.beacon figcaption{font-size:.9rem;color:#444;margin-top:.5rem}
.beacon .b-refs{font-size:.9rem}
.beacon .b-refs li{margin-bottom:.4rem}
.beacon textarea{width:100%;min-height:90px;border:1px solid var(--b-line);border-radius:6px;padding:.5rem;font:inherit}
.beacon .b-methods{border-left-color:var(--b-navy)}
.beacon .b-methods .b-label{background:var(--b-navy)}
.beacon .b-methods dl{margin:0;display:grid;grid-template-columns:minmax(0,9em) minmax(0,1fr);gap:.5rem 1rem}
.beacon .b-methods dt{font-weight:700;color:var(--b-navy)}
.beacon .b-methods dd{margin:0}
@media (max-width:600px){.beacon .b-methods dl{grid-template-columns:minmax(0,1fr)}.beacon .b-methods dd{margin-bottom:.5rem}}
.beacon .cite{font-size:.85em;text-decoration:none;font-weight:700}
.beacon .caution{font-size:.9rem;color:#555;border-top:1px solid var(--b-line);padding-top:.75rem;margin-top:1.75rem}
/* Interactive figure: research waste simulator (adapted from the improvement simulator) */
.beacon .b-sim{background:var(--b-bg);border:1px solid var(--b-line);border-left:6px solid var(--b-teal);border-radius:8px;padding:1rem 1.25rem;margin:1.75rem 0}
.beacon .b-sim h3{margin:.25rem 0 .25rem;font-size:1.15rem;color:var(--b-navy)}
.sim-presets{display:flex;flex-wrap:wrap;gap:8px;margin:12px 0}
.sim-presets button{font:inherit;font-size:15px;min-height:44px;padding:6px 14px;border:1px solid var(--b-teal);background:#fff;color:var(--b-teal);border-radius:22px;cursor:pointer}
.sim-presets button[aria-pressed=true]{background:var(--b-teal);color:#fff}
.sim-ctrl{display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1fr);gap:6px 20px;margin-bottom:14px}
@media(max-width:600px){.sim-ctrl{grid-template-columns:minmax(0,1fr)}}
.sim-ctrl label{display:grid;grid-template-columns:minmax(0,1fr) 2.2em;gap:2px 10px;align-items:center;font-size:15px}
.sim-ctrl label span{grid-column:1/-1;display:flex;align-items:center;gap:8px}
.sim-ctrl input{width:100%;min-height:32px;accent-color:var(--b-teal)}
.sim-ctrl output{font-weight:700;text-align:right;font-variant-numeric:tabular-nums}
.sw{display:inline-block;width:14px;height:14px;border-radius:3px;flex:none}
.s1{background:#8FA3B8}.s2{background:#B9C7D4}.s3{background:#D9E1E8;border:1px solid #b8c3cd}.s4{background:#1D7A74}
.sim-out{background:#fff;border:1px solid var(--b-line);border-radius:6px;padding:12px 14px}
.sim-row-t{font-weight:700;color:var(--b-navy);font-size:15px;margin:6px 0 6px!important}
.sim-row{display:grid;grid-template-columns:7.5em minmax(0,1fr) 3.2em;gap:10px;align-items:center;margin-bottom:8px;font-size:14px}
.sim-track{height:30px;background:repeating-linear-gradient(90deg,#f3f5f8 0 calc(10% - 1px),#e3e8ee calc(10% - 1px) 10%);border-radius:4px;display:flex;overflow:hidden}
.sim-track i{display:block;height:100%;transition:width .3s ease}
@media(prefers-reduced-motion:reduce){.sim-track i{transition:none}}
.sim-diff .sim-lab,.sim-diff .sim-val{color:var(--b-teal);font-weight:700}
.sim-val{font-weight:700;text-align:right;font-variant-numeric:tabular-nums}
.sim-read{margin:10px 0 0!important;padding-top:10px;border-top:1px solid var(--b-line);font-size:16px}
.sim-read strong{color:var(--b-teal)}
</style>

<div class="beacon">

Over the past two decades, research on exercise across the cancer continuum has grown remarkably. An international consensus statement now concludes that exercise is generally safe for people living with and beyond cancer, and that specific doses can improve anxiety, depressive symptoms, fatigue, physical function and health-related quality of life <a class="cite" href="#r1">[1]</a>. In 2025, a phase 3 randomised trial across 55 centres reported longer disease-free survival with a structured exercise programme after chemotherapy for colon cancer <a class="cite" href="#r2">[2]</a>.

That progress belongs to many people: researchers, clinicians, exercise professionals, advocates and, above all, the thousands of people affected by cancer who have given their time and effort to studies. It also brings responsibility. A field that hopes to change cancer care needs evidence that is rigorous, transparent and honestly interpreted.

That is why I am developing BEACON, and why I'm starting the BEACON Blog.

<div class="b-box b-takeaway" role="note" aria-label="Key takeaway">
<span class="b-label">Key takeaway</span>
<p>The future of exercise oncology depends less on producing more research than on producing better research: well designed, ethically conducted, fully reported and inclusive.</p>
</div>

## What BEACON is, and what the BEACON Blog will do

BEACON stands for Best practices in Exercise and physical ACtivity for Oncology research and traiNing. It is an educational resource for researchers, clinicians, exercise professionals, trainees and collaborators. As the name suggests, its aim is to shine a light on the methodological practices behind exercise oncology trials, from how they are designed and conducted to how they are analysed and reported. Some of those practices are strong and some need work, and seeing both clearly makes the path through a study easier to follow.

The resource has five parts, running from the foundations of the field to evaluating and translating evidence (Figure 1). Along the way it covers control groups, randomisation, blinding, sample size, trial monitoring, reporting, statistics, good clinical practice and evidence synthesis.

Each month, the BEACON Blog will take one idea from the resource and apply it to published exercise oncology research. I'll look at it through a trialist's eyes, connecting it to the landmark methods literature and to good clinical practice. Every post will include short interactive tasks, because appraisal is a skill you build by practising.

<figure>
<svg viewBox="0 0 720 430" role="img" aria-label="BEACON's five parts in order: foundations, trial fundamentals, statistical analysis, implementing research, and evidence evaluation and knowledge translation">
<rect x="0" y="0" width="720" height="430" rx="10" fill="#F5F7FA"/>
<path d="M60 70 V370" stroke="#C9821B" stroke-width="6" stroke-dasharray="2 12" stroke-linecap="round"/>
<g font-family="Helvetica, Arial, sans-serif">
<circle cx="60" cy="58" r="28" fill="#1F3A5F"/><text x="60" y="66" fill="#fff" font-size="22" font-weight="700" text-anchor="middle">I</text>
<text x="110" y="52" fill="#1F3A5F" font-size="21" font-weight="700">Foundations of exercise oncology research</text>
<text x="110" y="78" fill="#1E2430" font-size="17">Chapter 1: the field, its evidence base and its challenges</text>
<circle cx="60" cy="138" r="28" fill="#1D7A74"/><text x="60" y="146" fill="#fff" font-size="22" font-weight="700" text-anchor="middle">II</text>
<text x="110" y="132" fill="#1F3A5F" font-size="21" font-weight="700">Fundamentals of exercise oncology trials</text>
<text x="110" y="158" fill="#1E2430" font-size="17">Chapters 2 to 9: design, controls, randomisation, blinding, reporting</text>
<circle cx="60" cy="218" r="28" fill="#1F3A5F"/><text x="60" y="226" fill="#fff" font-size="22" font-weight="700" text-anchor="middle">III</text>
<text x="110" y="212" fill="#1F3A5F" font-size="21" font-weight="700">Statistical analysis</text>
<text x="110" y="238" fill="#1E2430" font-size="17">Chapters 10 to 16: description, inference, effect measures, adjustment</text>
<circle cx="60" cy="298" r="28" fill="#1D7A74"/><text x="60" y="306" fill="#fff" font-size="22" font-weight="700" text-anchor="middle">IV</text>
<text x="110" y="292" fill="#1F3A5F" font-size="21" font-weight="700">Implementing exercise oncology research</text>
<text x="110" y="318" fill="#1E2430" font-size="17">Chapters 17 to 23: planning, GCP, recruitment, quality, dissemination</text>
<circle cx="60" cy="378" r="28" fill="#1F3A5F"/><text x="60" y="386" fill="#fff" font-size="22" font-weight="700" text-anchor="middle">V</text>
<text x="110" y="372" fill="#1F3A5F" font-size="21" font-weight="700">Evidence evaluation and knowledge translation</text>
<text x="110" y="398" fill="#1E2430" font-size="17">Chapters 24 to 28: appraisal, GRADE, publication, systematic reviews</text>
</g>
</svg>
<figcaption><strong>Figure 1.</strong> The five parts of BEACON, from the foundations of the field to evaluating and translating evidence. Original diagram by Edward N. Stanhope for BEACON.</figcaption>
</figure>

## More research is not the same as better research

In 2009, Iain Chalmers and Paul Glasziou argued that most of the investment in health research is lost through avoidable failings <a class="cite" href="#r3">[3]</a>. Their estimate was that around 85% of research effort is wasted. The reasoning was simple: about half of studies are never published in full, about half of published reports are not usable, and about half of studies have avoidable design flaws <a class="cite" href="#r4">[4]</a>.

Multiply those halves together and only about one study in eight survives all three. That's 12.5%, which they rounded to a conservative estimate of 85% waste <a class="cite" href="#r4">[4]</a>. These are broad figures from across medical research, not exercise oncology specifically, and the authors set out the assumptions behind them <a class="cite" href="#r4">[4]</a>. But the logic is hard to escape, as you can see below.

<figure class="b-sim" data-waste aria-labelledby="sim-cap">
<div class="sim-head">
<span class="b-label">Try it</span>
<h3>More research or better research?</h3>
<p class="b-note">Change the number of studies, or how well each stage is done, or pick a scenario. Watch how many studies end up giving usable, trustworthy evidence.</p>
</div>
<div class="sim-presets" role="group" aria-label="Scenarios">
<button type="button" data-p="100,50,50,50" aria-pressed="true">The 2009 estimate</button>
<button type="button" data-p="200,50,50,50">Double the research</button>
<button type="button" data-p="100,75,75,75">Better research</button>
</div>
<div class="sim-ctrl">
<label><span><i class="sw s1"></i>Studies carried out</span><input type="range" min="0" max="300" step="10" value="100" data-k="0" aria-label="Studies carried out"><output>100</output></label>
<label><span><i class="sw s2"></i>% published in full</span><input type="range" min="0" max="100" step="5" value="50" data-k="1" aria-label="Percentage published in full"><output>50</output></label>
<label><span><i class="sw s3"></i>% of those reported well enough to use</span><input type="range" min="0" max="100" step="5" value="50" data-k="2" aria-label="Percentage of published studies reported well enough to use"><output>50</output></label>
<label><span><i class="sw s4"></i>% of those free of avoidable design flaws</span><input type="range" min="0" max="100" step="5" value="50" data-k="3" aria-label="Percentage of usable reports free of avoidable design flaws"><output>50</output></label>
</div>
<div class="sim-out">
<p class="sim-row-t">What happens to the research effort</p>
<div class="sim-row"><span class="sim-lab">Carried out</span><div class="sim-track" data-bar="run"></div><span class="sim-val" data-v="run"></span></div>
<div class="sim-row"><span class="sim-lab">Published</span><div class="sim-track" data-bar="pub"></div><span class="sim-val" data-v="pub"></span></div>
<div class="sim-row"><span class="sim-lab">Usable report</span><div class="sim-track" data-bar="rep"></div><span class="sim-val" data-v="rep"></span></div>
<div class="sim-row sim-diff"><span class="sim-lab">Usable evidence</span><div class="sim-track" data-bar="use"></div><span class="sim-val" data-v="use"></span></div>
<p class="sim-read" aria-live="polite" data-read></p>
</div>
<noscript><p class="b-note">This interactive figure needs JavaScript. In short: if half of studies fail at each of three stages, only 12.5 of every 100 give usable evidence. Doubling the number of studies doubles the waste too, while improving each stage to 75% raises usable evidence to about 42 in 100.</p></noscript>
<figcaption id="sim-cap"><strong>Figure 2.</strong> How avoidable waste compounds across stages. The "2009 estimate" preset uses the approximate 50% figures that Chalmers and Glasziou describe <a class="cite" href="#r3">[3]</a><a class="cite" href="#r4">[4]</a>; all other values are illustrative. Original interactive by Edward N. Stanhope for BEACON.</figcaption>
</figure>

Doubling the number of studies doubles the usable evidence, but it doubles the waste too. Improving each stage, even modestly, does more with the same effort. That is the case for better research rather than simply more of it.

## Evidence in action: how well do we describe our own interventions?

Exercise oncology is not immune. Meneses-Echavez and colleagues reviewed 131 randomised controlled trials of exercise for people with cancer, published between 2010 and 2017 <a class="cite" href="#r5">[5]</a>. They checked how completely the 138 exercise interventions were described against TIDieR, a checklist of what someone would need to know to deliver an intervention again.

None of the TIDieR items was fully reported across the trials <a class="cite" href="#r5">[5]</a>. Reporting of individual items ranged from 42% to 96%. Who delivered the exercise, and their expertise, was described for only 42% of interventions, and how well delivery was planned to be checked for only 46% <a class="cite" href="#r5">[5]</a>.

This shows that a large and growing evidence base can still be hard to use. If another team can't tell who delivered a programme, they can't reproduce it, and a service can't adopt it. None of that needs more trials to fix. The review covers trials up to 2017, so reporting may have improved since, but that is something to check rather than assume.

<section class="b-box b-methods" aria-labelledby="ml1">
<span class="b-label">Methods lens</span>
<h3 id="ml1">Avoidable research waste, and building quality in</h3>
<dl>
<dt>The principle</dt><dd>Research is wasted when it asks the wrong question, uses a design that can't answer it, goes unpublished, or is reported too poorly to use. Most of that waste is avoidable.</dd>
<dt>Why it matters here</dt><dd>Exercise interventions have many components (dose, progression, supervision, setting), so they are easy to under-report. Each incompletely reported trial asks participants to contribute to evidence that can't be fully used <a class="cite" href="#r5">[5]</a>.</dd>
<dt>Landmark evidence</dt><dd>Chalmers and Glasziou's 2009 <em>Lancet</em> paper set out how waste accumulates across the research process and estimated that around 85% of research investment is lost <a class="cite" href="#r3">[3]</a>.</dd>
<dt>GCP note</dt><dd>ICH E6(R3), in effect since July 2025, builds on the idea of designing quality into trials from the start, with a proportionate, risk-based approach <a class="cite" href="#r6">[6]</a>. It was written for medicines, but its principles are the expected standard for well-run exercise trials too.</dd>
</dl>
</section>

## Research with, not about, people affected by cancer

At the heart of every exercise oncology study are people who volunteer to take part. They give their time, energy and personal information, and often their hope that others will benefit. Research ethics therefore can't be a regulatory hurdle alone. It has to guide every step, from choosing the question to communicating the answer.

For that reason, I'd argue that a well-designed study is an ethical obligation, not a methodological luxury. People affected by cancer also bring expertise researchers lack: they know the barriers to taking part, the practical limits and which outcomes matter in daily life. Nothing about people affected by cancer without people affected by cancer.

Equity is part of this, and it is a methodological principle, not only a recruitment target. A systematic review of 28 prostate cancer exercise studies, with 15,946 participants, found that reporting of ethnicity varied widely and no study included a statement on inclusivity <a class="cite" href="#r7">[7]</a>. Few men from ethnic minority groups took part in the UK studies <a class="cite" href="#r7">[7]</a>. If research mostly includes the people easiest to recruit and retain, its findings may not apply to those who could benefit most.

<section class="b-box" aria-labelledby="gp1">
<span class="b-label">Good practice / poor practice</span>
<h3 id="gp1">Who takes part, and who shapes the study</h3>
<div class="b-compare">
<div class="b-card poor"><h4>✗ Poor practice</h4><p>Participants are recruited from whoever is easiest to reach, ethnicity is reported inconsistently, and the study has no statement on inclusivity. This pattern is common in prostate cancer exercise research <a class="cite" href="#r7">[7]</a>. People affected by cancer appear only as participants, and any involvement goes unreported.</p></div>
<div class="b-card good"><h4>✓ Good practice</h4><p>People affected by cancer, including from under-served groups, help shape the question, design and delivery. The team plans inclusive recruitment, reports who took part and who didn't, and describes involvement using the GRIPP2 short form, a five-item checklist covering aims, methods, results, outcomes and critical perspective <a class="cite" href="#r8">[8]</a>.</p></div>
</div>
</section>

## Ambition and rigour are not competing positions

Questions about exercise, tumour biology, treatment response and survival are important frontiers, and ambitious research is essential. But evidence must be described at its actual maturity. Early mechanistic findings, exploratory analyses and hypothesis-generating studies are valuable, and they should be labelled as such.

I find it helpful to hold two ideas together. Exercise has enormous potential to improve the lives of people affected by cancer. The evidence for that potential must keep getting stronger. Together, they are the foundation of a trustworthy discipline.

<section class="b-box" aria-labelledby="me1">
<span class="b-label">Myth or evidence?</span>
<h3 id="me1">Decide what you think, then reveal the verdict</h3>
<details><summary>“Exercise is safe and helpful for people living with and beyond cancer.”</summary><div><strong>Verdict: supported, with specifics.</strong> An international consensus found exercise training and testing generally safe, with enough evidence that specific doses improve anxiety, depressive symptoms, fatigue, physical function and health-related quality of life. Effects on other outcomes, such as peripheral neuropathy and cognitive function, remain uncertain <a class="cite" href="#r1">[1]</a>.</div></details>
<details><summary>“The evidence now shows that exercise cures cancer.”</summary><div><strong>Verdict: not supported.</strong> The CHALLENGE trial found longer disease-free survival with structured exercise after chemotherapy for colon cancer <a class="cite" href="#r2">[2]</a>. That is an important result, but it is one trial, in one cancer, at one point in care. It shows a benefit alongside treatment, not a cure.</div></details>
<details><summary>“More studies will settle the questions that remain.”</summary><div><strong>Verdict: not on their own.</strong> If studies are poorly designed, unpublished or incompletely reported, adding more of them adds waste as well as evidence <a class="cite" href="#r3">[3]</a>. Better-designed and better-reported studies are what strengthen the evidence base.</div></details>
</section>

<section class="b-box" aria-labelledby="rp1">
<span class="b-label">Reflect</span>
<h3 id="rp1">Think of a study you are planning, running or reading. Is the question important? Will it meaningfully advance knowledge? Does it respect participants' contributions? Are the conclusions proportionate, and is uncertainty communicated honestly? Which is hardest to answer "yes" to?</h3>
<label for="rp1-notes" class="b-note">Jot down your thoughts (they stay in your browser and aren't saved or sent anywhere):</label>
<textarea id="rp1-notes"></textarea>
</section>

<section class="b-box" aria-labelledby="kc1">
<span class="b-label">Check your understanding</span>
<h3 id="kc1">Question 1. A small exercise trial finds an exploratory change in a blood biomarker linked to tumour growth. Which summary is most proportionate?</h3>
<p class="b-note">Choose an answer to see the feedback.</p>
<details><summary>A. "Exercise slows tumour growth."</summary><div><span class="b-incorrect">Not quite.</span> A biomarker change is not a clinical outcome, and an exploratory finding in a small trial can't establish an effect on tumours. This claim goes well beyond the evidence.</div></details>
<details><summary>B. "This exploratory finding is hypothesis-generating and needs testing in larger trials with clinical outcomes."</summary><div><span class="b-correct">Correct.</span> It names the finding's maturity, keeps it valuable, and says what would be needed to make a stronger claim.</div></details>
<details><summary>C. "The finding should be ignored because it is exploratory."</summary><div><span class="b-incorrect">Not quite.</span> Exploratory findings are valuable contributions to science. The issue is how they are described, not whether they are shared.</div></details>
<details><summary>D. "Exercise may cure some cancers."</summary><div><span class="b-incorrect">Not quite.</span> No current evidence supports a claim of cure, and this wording could raise unrealistic expectations among people affected by cancer.</div></details>
<h3>Question 2. Using the "2009 estimate" in Figure 2, which change produces the most usable evidence from the same effort?</h3>
<details><summary>A. Running twice as many studies</summary><div><span class="b-incorrect">Not quite.</span> That doubles the usable studies, from 12.5 to 25, but it also doubles the effort, so 87.5% is still wasted.</div></details>
<details><summary>B. Improving publication, reporting and design so that each reaches 75%</summary><div><span class="b-correct">Correct.</span> With the same 100 studies, usable evidence rises to about 42. Because losses multiply across stages, modest improvements at each stage add up <a class="cite" href="#r3">[3]</a>.</div></details>
<details><summary>C. Improving reporting to 100% but leaving the other stages unchanged</summary><div><span class="b-incorrect">Not quite.</span> Usable evidence rises to 25, but studies that are never published, or have avoidable design flaws, are still lost.</div></details>
<h3>Question 3. Why is equity described as a methodological principle, not only a recruitment target?</h3>
<details><summary>A. Because funders require it</summary><div><span class="b-incorrect">Not quite.</span> Funders may ask for it, but the reason is scientific: it affects what the evidence can tell us.</div></details>
<details><summary>B. Because who takes part determines who the findings apply to</summary><div><span class="b-correct">Correct.</span> If some groups are missing, we can't be confident that the results apply to them. Under-representation and patchy reporting limit how far findings travel <a class="cite" href="#r7">[7]</a>.</div></details>
<details><summary>C. Because diverse samples always give larger effects</summary><div><span class="b-incorrect">Not quite.</span> There's no reason to expect that. The point is applicability, not effect size.</div></details>
</section>

## What this means in practice

- **If you design or run studies:** ask whether the question matters and whether the design can answer it, plan to publish whatever the result, and report the intervention fully (TIDieR) and involvement transparently (GRIPP2).
- **If you are a clinician or exercise professional:** look for how an intervention was delivered and who took part before deciding whether a finding applies to the people you work with.
- **If you are a trainee:** constructive critique is how the field improves. Asking difficult questions about design is a contribution, not a challenge to anyone.
- **If you are affected by cancer:** you can help shape research, not only take part in it. It is also reasonable to ask how strong the evidence behind a claim is.

## An invitation

The strongest future for exercise oncology will rest less on how much research we produce than on how well we design, conduct, report and share it. BEACON exists to help with that, and the BEACON Blog will shine its light on our field's trial methods, one practice at a time.

**Read the BEACON Background and Chapter 1 at [BEACON URL], and tell me in the comments which topic you'd like the BEACON Blog to tackle first.**

<p class="caution">This post discusses research design and is not individual medical advice. If you are affected by cancer and thinking about starting a new exercise programme, talk to your care team first.</p>

**Funding and competing interests.** BEACON is unfunded. I am a researcher active in exercise oncology, and my views are shaped by my educational, clinical and research experience.

## References

1. <span id="r1"></span>Campbell KL, Winters-Stone KM, Wiskemann J, May AM, Schwartz AL, Courneya KS, et al. Exercise guidelines for cancer survivors: consensus statement from international multidisciplinary roundtable. *Med Sci Sports Exerc*. 2019;51(11):2375-90. [doi:10.1249/MSS.0000000000002116](https://doi.org/10.1249/MSS.0000000000002116) 🔓 Free author manuscript: [PMC8576825](https://pmc.ncbi.nlm.nih.gov/articles/PMC8576825)
2. <span id="r2"></span>Courneya KS, Vardy JL, O'Callaghan CJ, Gill S, Friedenreich CM, Wong RKS, et al. Structured exercise after adjuvant chemotherapy for colon cancer. *N Engl J Med*. 2025;393(1):13-25. [doi:10.1056/NEJMoa2502760](https://doi.org/10.1056/NEJMoa2502760) 🔒 Subscription
3. <span id="r3"></span>Chalmers I, Glasziou P. Avoidable waste in the production and reporting of research evidence. *Lancet*. 2009;374(9683):86-9. [doi:10.1016/S0140-6736(09)60329-9](https://doi.org/10.1016/S0140-6736(09)60329-9) 🔒 Subscription (landmark paper)
4. <span id="r4"></span>Glasziou P, Chalmers I. Is 85% of health research really "wasted"? *The BMJ Opinion* [blog]. 14 January 2016. [blogs.bmj.com](https://blogs.bmj.com/bmj/2016/01/14/paul-glasziou-and-iain-chalmers-is-85-of-health-research-really-wasted/) 🔓 Open access
5. <span id="r5"></span>Meneses-Echavez JF, Rodriguez-Prieto I, Elkins M, Martínez-Torres J, Nguyen L, Bidonde J. Analysis of reporting completeness in exercise cancer trials: a systematic review. *BMC Med Res Methodol*. 2019;19:220. [doi:10.1186/s12874-019-0871-0](https://doi.org/10.1186/s12874-019-0871-0) 🔓 Open access: [PMC6889190](https://pmc.ncbi.nlm.nih.gov/articles/PMC6889190)
6. <span id="r6"></span>International Council for Harmonisation. ICH E6(R3) Guideline for good clinical practice: principles and Annex 1. Effective 23 July 2025. [European Medicines Agency](https://www.ema.europa.eu/en/scientific-guidelines/ich-e6-good-clinical-practice) 🔓 Open access
7. <span id="r7"></span>Ashton RE, Faghy MA, Roscoe CMP, Aning J. Inclusivity in prostate cancer and exercise research: a systematic review. *Support Care Cancer*. 2024;32(9):616. [doi:10.1007/s00520-024-08793-9](https://doi.org/10.1007/s00520-024-08793-9) 🔓 Open access: [PMC11358357](https://pmc.ncbi.nlm.nih.gov/articles/PMC11358357)
8. <span id="r8"></span>Staniszewska S, Brett J, Simera I, Seers K, Mockford C, Goodlad S, et al. GRIPP2 reporting checklists: tools to improve reporting of patient and public involvement in research. *BMJ*. 2017;358:j3453. [doi:10.1136/bmj.j3453](https://doi.org/10.1136/bmj.j3453) 🔓 Open access: [PMC5539518](https://pmc.ncbi.nlm.nih.gov/articles/PMC5539518)

🔓 Open access · 🔒 Subscription. Open versions are linked where available.

## Further reading

- BEACON Background and Chapter 1: Introduction to exercise oncology research *([BEACON URL])*
- [EQUATOR Network](https://www.equator-network.org/): reporting guidelines including CONSORT, SPIRIT, TIDieR, CERT and GRIPP2
- [ICH E6(R3) at the European Medicines Agency](https://www.ema.europa.eu/en/scientific-guidelines/ich-e6-good-clinical-practice): the current good clinical practice guideline

</div>

<script>
{
document.querySelectorAll('[data-waste]').forEach(sim => {
const ins=[...sim.querySelectorAll('input[type=range]')], btns=[...sim.querySelectorAll('[data-p]')], MAX=300;
const fmt=x=>Math.abs(x-Math.round(x))<0.05?String(Math.round(x)):x.toFixed(1);
const set=(k,v,c)=>{sim.querySelector(`[data-bar="${k}"]`).innerHTML=v>0?`<i class="${c}" style="width:${v/MAX*100}%"></i>`:'';sim.querySelector(`[data-v="${k}"]`).textContent=fmt(v)};
const render=()=>{
const v=ins.map(i=>+i.value); ins.forEach((i,k)=>i.nextElementSibling.textContent=v[k]);
const n=v[0], pub=n*v[1]/100, rep=pub*v[2]/100, use=rep*v[3]/100;
set('run',n,'s1'); set('pub',pub,'s2'); set('rep',rep,'s3'); set('use',use,'s4');
const pct=n?use/n*100:0;
sim.querySelector('[data-read]').innerHTML = n===0 ? 'No studies, no evidence.' :
`Of <strong>${n}</strong> studies, about <strong>${fmt(use)}</strong> are published, usable and free of avoidable design flaws. That is ${fmt(pct)}% of the effort; the other ${fmt(100-pct)}% is avoidable waste.`;
};
ins.forEach(i=>i.addEventListener('input',()=>{btns.forEach(b=>b.setAttribute('aria-pressed','false'));render()}));
btns.forEach(b=>b.addEventListener('click',()=>{b.dataset.p.split(',').forEach((x,k)=>ins[k].value=x);btns.forEach(o=>o.setAttribute('aria-pressed',String(o===b)));render()}));
render();
});
}
</script>
