<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0:0D1025,50:29389A,100:C5E654&text=hey,%20I'm%20Sujit%20%F0%9F%91%8B&fontColor=ffffff&fontSize=46&fontAlignY=40" alt="hey, I'm Sujit" />
</p>

<p align="center">
  <img src="./assets/terminal.svg" width="100%" alt="Terminal: whoami prints Sujit Shiravle, AI and full-stack developer. show-evals knowledgebot prints citation accuracy 15/15 (was 10/15), off-topic refusal 5/5 (was 4/5), red-team 10/10 (was 6/7). 3 bugs caught, 3 fixed, 3 regression tests." />
</p>

<p align="center">
  <a href="https://sujitspark.in"><img src="https://img.shields.io/badge/portfolio-sujitspark.in-0D1025?style=for-the-badge&logo=googlechrome&logoColor=C5E654" /></a>
  <a href="https://www.linkedin.com/in/sujit-shiravle"><img src="https://img.shields.io/badge/linkedin-sujit--shiravle-29389A?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:shiravlesujit@gmail.com"><img src="https://img.shields.io/badge/email-say%20hi-C5E654?style=for-the-badge&logo=gmail&logoColor=0D1025" /></a>
  <img src="https://img.shields.io/badge/open%20to-internships%20%26%202027%20roles-0D1025?style=for-the-badge&logoColor=white" />
</p>

<p align="center"><i>Final-year B.Tech AI &amp; Data Science · Navi Mumbai · I build LLM apps, then I try to break them.</i></p>

---

## 🧪 How I build AI

<p align="center">
  <img src="./assets/pipeline.svg" width="100%" alt="Pipeline: question, retrieve with pgvector, generate with an LLM, guardrails, judge with DeepEval, cited answer." />
</p>

<details>
<summary><b>🔬 My 5-step playbook for testing an LLM app</b> <i>(click to open)</i></summary>
<br>

1. **Write the exam first.** A golden dataset with real answers, questions the bot *must refuse*, and attacks.
2. **Test the real thing.** Evals hit the live API, not a copy of the pipeline.
3. **Trust, but calibrate.** Cheap deterministic checks gate a release; LLM-as-judge scores are a signal I check against human review.
4. **Attack with phrasings I didn't train on.** If the guardrail only stops the attacks I wrote, it isn't a guardrail.
5. **Every bug becomes a regression test**, and CI runs them on every push.

That's how KnowledgeBot went from 67% to 100% citation accuracy, and how a benchmark caught JudicAI's risk model reading its own answer key.
</details>

---

## 🚀 Things I've built

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [KnowledgeBot](https://github.com/SujitSpark/knowledgebot)
Chat with your PDFs, **100% offline**.
`React Native` `PostGraphile` `pgvector` `Ollama`

🧪 DeepEval + promptfoo eval and red-team suite · guardrails · CI

</td>
<td width="50%" valign="top">

### ⚖️ [JudicAI](https://github.com/SujitSpark/JudicAi)
Multi-agent triage for court backlogs.
`LangGraph` `FastAPI` `React` `XGBoost` `Gemini`

📊 1,200-case benchmark · leakage bug found and fixed · AUC 0.60 → 0.65

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 [PriceWar](https://github.com/SujitSpark/price_war)
Game theory for food-delivery price wars: Nash, Bertrand, Bayesian and repeated games.
`FastAPI` `React` `TypeScript`

</td>
<td width="50%" valign="top">

### 💬 [Emotion-Aware Dialogue](https://github.com/SujitSpark/NLP)
Detects 27 fine-grained emotions, picks an empathy strategy, then lets an LLM reply. *Team project.*
`PyTorch` `Transformers` `Gradio`

</td>
</tr>
</table>

---

## 📜 `git log --oneline --career`

```diff
+ 2026-11  feat(evals): red-team suite for KnowledgeBot, 3 bugs caught, 3 fixed
+ 2026-07  docs(research): co-authored IEEE I2ITCON 2026 paper on an AutoML learning platform
+ 2026-06  feat: KnowledgeBot, an offline RAG assistant (pgvector + Ollama)
+ 2026-03  ctf: 4th place, Technovate'26 Capture The Flag
+ 2026-02  feat: JudicAI, multi-agent judicial triage (LangGraph + FastAPI)
@ 2025-10  job: SDE Intern @ Infidhi Ventures (React Native + GraphQL/PostgreSQL)
@ 2025-08  job: Junior Intern @ Infidhi Ventures (PERN stack + RAG over internal docs)
@ 2024-12  job: Web Developer Intern @ Nexon Logistics (Firebase event booking)
+ 2024-06  feat: SIES GST Student Portal, used by 4,000+ students, 12,000+ forms
+ 2024     win: 2nd Runner Up, SustainX 2024
  2023-06  init: B.Tech AI & Data Science @ SIES GST
```

---

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,java,cpp,react,nodejs,express,fastapi,graphql,postgres,mongodb,firebase,docker,kubernetes,git,github&perline=9" alt="Python, TypeScript, JavaScript, Java, C++, React, Node.js, Express, FastAPI, GraphQL, PostgreSQL, MongoDB, Firebase, Docker, Kubernetes, Git, GitHub" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/DeepEval-29389A?style=flat-square" />
  <img src="https://img.shields.io/badge/promptfoo-C5E654?style=flat-square&labelColor=0D1025" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-EB5B25?style=flat-square" />
</p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SujitSpark/Sujitspark/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/SujitSpark/Sujitspark/output/github-snake.svg" alt="Contribution snake" />
  </picture>
</p>

<p align="center"><sub>⚡ Ask me about: why an R² of 1.00 is a red flag · making a chatbot say "PWNED" · RAG that runs with no internet</sub></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:C5E654,50:29389A,100:0D1025" alt="" />
</p>
