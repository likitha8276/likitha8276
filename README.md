<div align="center">

<img src="./assets/header.svg" alt="Chirreddy Likitha — Backend, AI/ML and Data" width="100%">

</div>

<img src="./assets/sec-profile.svg" alt="01 — Agent Profile" width="100%">

I'm a fourth-year CS student at **VIT-AP University** (graduating 2027) working across backend engineering, applied ML, and data-driven applications.

**I build systems, explore intelligent solutions, and keep learning how the pieces fit together.**

My projects follow one pattern: take a messy real-world problem (mismatched descriptions, raw CSVs, polluted routes), put an API or interface around it, and let ML do the part that rules can't.

<table>
  <tr><td><b>BASE</b></td><td>VIT-AP University, Amaravati · B.Tech CSE · 2027</td></tr>
  <tr><td><b>CORE STACK</b></td><td>Python · Java · SQL · FastAPI · Spring Boot</td></tr>
  <tr><td><b>FOCUS</b></td><td>Backend APIs · embeddings &amp; anomaly detection · data storytelling</td></tr>
  <tr><td><b>ROLE</b></td><td>Hybrid: software engineering + applied AI</td></tr>
</table>

<img src="./assets/sec-builds.svg" alt="02 — Match History: featured builds" width="100%">

<a href="https://github.com/likitha8276/ai-lost-and-found"><img src="./assets/card-1.svg" alt="Project 01 — AI Lost & Found System" width="100%"></a>

> **Problem:** keyword search can't connect "black leather wallet" with "dark billfold with cards".
> **Approach:** text and photos become embeddings, compared with cosine similarity. A deterministic matching layer turns scores into ranked candidates, so results are reproducible.
> **Interesting:** CLIP shares one space for text and images, so a written description can match a photo directly.

```text
text report  ──► MPNet ─┐
                        ├──► cosine similarity ──► ranked candidates   (FastAPI)
photo / text ──► CLIP ──┘
```

[**→ Repository**](https://github.com/likitha8276/ai-lost-and-found)

<br>

<a href="https://github.com/likitha8276/ai-dataset-storytelling-api"><img src="./assets/card-2.svg" alt="Project 02 — DataSense: AI Dataset Storytelling API" width="100%"></a>

> **Problem:** raw tables and summary stats show numbers, not meaning.
> **Approach:** upload a CSV → clean → summaries and correlations → anomaly flags → LLM narration, with a rule-based fallback when the LLM is unavailable.
> **Interesting:** pipeline, two anomaly methods, auth, and graceful LLM degradation in one API.

| Layer | What it does |
|:--|:--|
| **Data** | Pandas cleaning, statistical summaries, correlation analysis |
| **Detection** | Isolation Forest + linear-regression residuals |
| **Narration** | Gemini explanations, rule-based fallback |
| **Platform** | FastAPI · JWT auth · SQLite · Streamlit dashboard |

[**→ Repository**](https://github.com/likitha8276/ai-dataset-storytelling-api)

<br>

<img src="./assets/card-3.svg" alt="Project 03 — AQI Intelligence and pollution-aware navigation" width="100%">

> **Problem:** navigation apps optimise for time, not for how much polluted air a route exposes you to.
> **Approach:** Linear Regression forecasts PM2.5, areas are classified into pollution zones, and routes are offered in three modes on a Folium map inside Streamlit.
> **Interesting:** environmental data, predictive modelling, and geographic visualisation in one decision-support tool.

| Mode | Optimises for |
|:--|:--|
| **Eco** | Lowest pollution exposure |
| **Fastest** | Shortest travel time |
| **Balanced** | Trade-off between the two |

<!-- TODO: uncomment once the AQI repo is public, replace the URL
[**→ Repository**](https://github.com/likitha8276/YOUR-AQI-REPO-NAME)
-->

<img src="./assets/sec-loadout.svg" alt="03 — Loadout: skills by area" width="100%">

<table>
  <tr><td width="28%"><b>LANGUAGES</b></td><td>Java · Python · SQL</td></tr>
  <tr><td><b>BACKEND &amp; DATA STORES</b></td><td>Spring Boot · FastAPI · REST APIs · JWT auth · PostgreSQL · Redis · SQLite</td></tr>
  <tr><td><b>AI / ML / DATA</b></td><td>Scikit-learn · Pandas · Linear Regression · K-Means · anomaly detection · statistical analysis · MPNet &amp; CLIP embeddings · LLM integration (Gemini)</td></tr>
  <tr><td><b>TOOLS</b></td><td>Git/GitHub · IntelliJ IDEA · Streamlit · Figma · Canva</td></tr>
</table>

<sub>Depth varies by area. The builds above show where I've applied each thing.</sub>

<img src="./assets/sec-rounds.svg" alt="04 — Round Log: problem-solving" width="100%">

An ongoing practice, not a finished one.

**Covered so far:** arrays · hashing · binary search · Merge Sort &amp; Quick Sort · trees · BFS / DFS
**Patterns practised:** Boyer–Moore majority vote · anagram grouping · stock-profit optimisation · tree traversals

<img src="./assets/sec-next.svg" alt="05 — Next Round: currently exploring" width="100%">

- Stronger backend fundamentals: Spring Boot, PostgreSQL, Redis
- Better ways to evaluate and explain ML outputs

<img src="./assets/sec-activity.svg" alt="06 — Match Activity: GitHub contributions" width="100%">

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=likitha8276&bg_color=0F1923&color=FF4655&line=FF4655&point=FFFFFF&area=true&area_color=FF4655&hide_border=true&title_color=FFFFFF&radius=6" alt="GitHub contribution activity graph" width="100%">

</div>

<img src="./assets/sec-comms.svg" alt="07 — Comms: contact" width="100%">

[**GitHub — @likitha8276**](https://github.com/likitha8276)
<!-- TODO: uncomment and add your real LinkedIn URL
 · [**LinkedIn**](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)
-->

<sub>Open to feedback, ideas, and collaboration on backend and applied-AI projects.</sub>

<img src="./assets/divider.svg" width="100%" alt="">
