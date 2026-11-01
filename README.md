<div align="center">

<img src="./assets/header.svg" alt="Chirreddy Likitha — Backend, AI/ML and Data" width="100%">

</div>

<img src="./assets/divider.svg" width="100%" alt="">

### 01 / PROFILE

I'm a fourth-year CS student at **VIT-AP University** (graduating 2027) working across backend engineering, applied ML, and data-driven applications.

**I build systems, explore intelligent solutions, and keep learning how the pieces fit together.**

My projects follow one pattern: take a messy real-world problem (mismatched descriptions, raw CSVs, polluted routes), put an API or interface around it, and let ML do the part that rules can't.

<table>
  <tr>
    <td><b>Base</b></td>
    <td>VIT-AP University, Amaravati · B.Tech CSE · 2027</td>
  </tr>
  <tr>
    <td><b>Core stack</b></td>
    <td>Python · Java · SQL · FastAPI · Spring Boot</td>
  </tr>
  <tr>
    <td><b>Working on</b></td>
    <td>Backend APIs · embeddings &amp; anomaly detection · data storytelling</td>
  </tr>
  <tr>
    <td><b>Profile</b></td>
    <td>Hybrid: software engineering + applied AI</td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="">

### 02 / FEATURED BUILDS

#### ▌PROJECT 01 — AI Lost &amp; Found System
**Matches lost-item reports to found-item reports by meaning and appearance, not exact keywords.**

> **Problem:** Lost-and-found systems rely on keyword search or manual browsing, so "black leather wallet" never meets "dark billfold with cards".
>
> **Approach:** Descriptions and photos are both converted to embeddings, then compared with cosine similarity. A deterministic matching layer turns scores into candidate matches, so results are reproducible and explainable.

```text
text report  ──► MPNet ─┐
                        ├──► cosine similarity ──► ranked candidate matches
photo / text ──► CLIP ──┘            (FastAPI)
```

**Stack:** `Python` · `FastAPI` · `MPNet` · `CLIP` · `Cosine Similarity`

**Why it's interesting:** CLIP puts text and images in the same space, so a written description can be matched directly against a photo.

[**→ View repository**](https://github.com/likitha8276/ai-lost-and-found)

<br>

#### ▌PROJECT 02 — DataSense: AI Dataset Storytelling API
**Turns an uploaded CSV into statistical findings and a plain-language explanation.**

> **Problem:** Raw tables and summary stats show numbers but not what they mean.
>
> **Approach:** Upload a CSV, then clean it, compute summaries and correlations, flag anomalies, and have an LLM narrate the findings. If the LLM is unavailable, a rule-based narrator takes over, so the API still returns an explanation.

| Layer | What it does |
|:--|:--|
| **Data** | Pandas cleaning, statistical summaries, correlation analysis |
| **Detection** | Isolation Forest + linear-regression residuals for anomalies |
| **Narration** | Gemini explanations with a rule-based fallback |
| **Platform** | FastAPI · JWT auth · SQLite · Streamlit dashboard |

**Why it's interesting:** It combines the data pipeline, two anomaly-detection methods, auth, and LLM integration with graceful degradation, so it behaves like a small product rather than a notebook.

[**→ View repository**](https://github.com/likitha8276/ai-dataset-storytelling-api)

<br>

#### ▌PROJECT 03 — AQI Intelligence + Pollution-Aware Navigation
**Forecasts PM2.5 for Delhi and recommends routes based on pollution exposure.**

> **Problem:** Navigation apps optimise for time. They don't tell you how much polluted air a route puts you through.
>
> **Approach:** A Linear Regression model forecasts PM2.5, areas are classified into pollution zones, and routes are offered in three modes and shown on a Folium map in a Streamlit app.

| Mode | Optimises for |
|:--|:--|
| **Eco** | Lowest pollution exposure |
| **Fastest** | Shortest travel time |
| **Balanced** | Trade-off between the two |

**Stack:** `Python` · `Streamlit` · `Scikit-learn` · `Folium`

**Why it's interesting:** It joins environmental data, predictive modelling, and geographic visualisation in one decision-support tool.

<!-- TODO: uncomment once the AQI repo is public, and replace the URL
[**→ View repository**](https://github.com/likitha8276/YOUR-AQI-REPO-NAME)
-->

<img src="./assets/divider.svg" width="100%" alt="">

### 03 / SKILL MAP

<table>
  <tr>
    <td width="30%"><b>Languages</b></td>
    <td>Java · Python · SQL</td>
  </tr>
  <tr>
    <td><b>Backend &amp; data stores</b></td>
    <td>Spring Boot · FastAPI · REST APIs · JWT auth · PostgreSQL · Redis · SQLite</td>
  </tr>
  <tr>
    <td><b>AI / ML / data</b></td>
    <td>Scikit-learn · Pandas · Linear Regression · K-Means · anomaly detection · statistical analysis · MPNet &amp; CLIP embeddings · LLM integration (Gemini)</td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>Git/GitHub · IntelliJ IDEA · Streamlit · Figma · Canva</td>
  </tr>
</table>

<sub>Depth varies by area. The project sections above show where I've applied each thing.</sub>

<img src="./assets/divider.svg" width="100%" alt="">

### 04 / PROBLEM-SOLVING LOG

An ongoing practice, not a finished one.

**Covered so far:** arrays · hashing · binary search · Merge Sort &amp; Quick Sort · trees · BFS / DFS
**Patterns practised:** Boyer–Moore majority vote · anagram grouping · stock-profit optimisation · tree traversals

<img src="./assets/divider.svg" width="100%" alt="">

### 05 / CURRENTLY EXPLORING

- Stronger backend fundamentals: Spring Boot, PostgreSQL, Redis
- Better ways to evaluate and explain ML outputs

<img src="./assets/divider.svg" width="100%" alt="">

### 06 / ACTIVITY

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=likitha8276&bg_color=0F1923&color=FF4655&line=FF4655&point=FFFFFF&area=true&area_color=FF4655&hide_border=true&title_color=FFFFFF&radius=6" alt="GitHub contribution activity graph" width="100%">

</div>

<img src="./assets/divider.svg" width="100%" alt="">

### 07 / CONTACT

[**GitHub — @likitha8276**](https://github.com/likitha8276)
<!-- TODO: uncomment and replace with your real LinkedIn URL
 · [**LinkedIn**](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)
-->

<sub>Open to feedback, ideas, and collaboration on backend and applied-AI projects.</sub><div align="center">

<img src="./assets/header.svg" alt="Chirreddy Likitha — Backend, AI/ML and Data" width="100%">

</div>

<img src="./assets/divider.svg" width="100%" alt="">

### 01 / PROFILE

I'm a fourth-year CS student at **VIT-AP University** (graduating 2027) working across backend engineering, applied ML, and data-driven applications.

**I build systems, explore intelligent solutions, and keep learning how the pieces fit together.**

My projects follow one pattern: take a messy real-world problem (mismatched descriptions, raw CSVs, polluted routes), put an API or interface around it, and let ML do the part that rules can't.

<table>
  <tr>
    <td><b>Base</b></td>
    <td>VIT-AP University, Amaravati · B.Tech CSE · 2027</td>
  </tr>
  <tr>
    <td><b>Core stack</b></td>
    <td>Python · Java · SQL · FastAPI · Spring Boot</td>
  </tr>
  <tr>
    <td><b>Working on</b></td>
    <td>Backend APIs · embeddings &amp; anomaly detection · data storytelling</td>
  </tr>
  <tr>
    <td><b>Profile</b></td>
    <td>Hybrid: software engineering + applied AI</td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="">

### 02 / FEATURED BUILDS

#### ▌PROJECT 01 — AI Lost &amp; Found System
**Matches lost-item reports to found-item reports by meaning and appearance, not exact keywords.**

> **Problem:** Lost-and-found systems rely on keyword search or manual browsing, so "black leather wallet" never meets "dark billfold with cards".
>
> **Approach:** Descriptions and photos are both converted to embeddings, then compared with cosine similarity. A deterministic matching layer turns scores into candidate matches, so results are reproducible and explainable.

```text
text report  ──► MPNet ─┐
                        ├──► cosine similarity ──► ranked candidate matches
photo / text ──► CLIP ──┘            (FastAPI)
```

**Stack:** `Python` · `FastAPI` · `MPNet` · `CLIP` · `Cosine Similarity`

**Why it's interesting:** CLIP puts text and images in the same space, so a written description can be matched directly against a photo.

[**→ View repository**](https://github.com/likitha8276/ai-lost-and-found)

<br>

#### ▌PROJECT 02 — DataSense: AI Dataset Storytelling API
**Turns an uploaded CSV into statistical findings and a plain-language explanation.**

> **Problem:** Raw tables and summary stats show numbers but not what they mean.
>
> **Approach:** Upload a CSV, then clean it, compute summaries and correlations, flag anomalies, and have an LLM narrate the findings. If the LLM is unavailable, a rule-based narrator takes over, so the API still returns an explanation.

| Layer | What it does |
|:--|:--|
| **Data** | Pandas cleaning, statistical summaries, correlation analysis |
| **Detection** | Isolation Forest + linear-regression residuals for anomalies |
| **Narration** | Gemini explanations with a rule-based fallback |
| **Platform** | FastAPI · JWT auth · SQLite · Streamlit dashboard |

**Why it's interesting:** It combines the data pipeline, two anomaly-detection methods, auth, and LLM integration with graceful degradation, so it behaves like a small product rather than a notebook.

[**→ View repository**](https://github.com/likitha8276/ai-dataset-storytelling-api)

<br>

#### ▌PROJECT 03 — AQI Intelligence + Pollution-Aware Navigation
**Forecasts PM2.5 for Delhi and recommends routes based on pollution exposure.**

> **Problem:** Navigation apps optimise for time. They don't tell you how much polluted air a route puts you through.
>
> **Approach:** A Linear Regression model forecasts PM2.5, areas are classified into pollution zones, and routes are offered in three modes and shown on a Folium map in a Streamlit app.

| Mode | Optimises for |
|:--|:--|
| **Eco** | Lowest pollution exposure |
| **Fastest** | Shortest travel time |
| **Balanced** | Trade-off between the two |

**Stack:** `Python` · `Streamlit` · `Scikit-learn` · `Folium`

**Why it's interesting:** It joins environmental data, predictive modelling, and geographic visualisation in one decision-support tool.

<!-- TODO: uncomment once the AQI repo is public, and replace the URL
[**→ View repository**](https://github.com/likitha8276/YOUR-AQI-REPO-NAME)
-->

<img src="./assets/divider.svg" width="100%" alt="">

### 03 / SKILL MAP

<table>
  <tr>
    <td width="30%"><b>Languages</b></td>
    <td>Java · Python · SQL</td>
  </tr>
  <tr>
    <td><b>Backend &amp; data stores</b></td>
    <td>Spring Boot · FastAPI · REST APIs · JWT auth · PostgreSQL · Redis · SQLite</td>
  </tr>
  <tr>
    <td><b>AI / ML / data</b></td>
    <td>Scikit-learn · Pandas · Linear Regression · K-Means · anomaly detection · statistical analysis · MPNet &amp; CLIP embeddings · LLM integration (Gemini)</td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>Git/GitHub · IntelliJ IDEA · Streamlit · Figma · Canva</td>
  </tr>
</table>

<sub>Depth varies by area. The project sections above show where I've applied each thing.</sub>

<img src="./assets/divider.svg" width="100%" alt="">

### 04 / PROBLEM-SOLVING LOG

An ongoing practice, not a finished one.

**Covered so far:** arrays · hashing · binary search · Merge Sort &amp; Quick Sort · trees · BFS / DFS
**Patterns practised:** Boyer–Moore majority vote · anagram grouping · stock-profit optimisation · tree traversals

<img src="./assets/divider.svg" width="100%" alt="">

### 05 / CURRENTLY EXPLORING

- Stronger backend fundamentals: Spring Boot, PostgreSQL, Redis
- Better ways to evaluate and explain ML outputs

<img src="./assets/divider.svg" width="100%" alt="">

### 06 / ACTIVITY

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=likitha8276&bg_color=0F1923&color=FF4655&line=FF4655&point=FFFFFF&area=true&area_color=FF4655&hide_border=true&title_color=FFFFFF&radius=6" alt="GitHub contribution activity graph" width="100%">

</div>

<img src="./assets/divider.svg" width="100%" alt="">

### 07 / CONTACT

[**GitHub — @likitha8276**](https://github.com/likitha8276)
<!-- TODO: uncomment and replace with your real LinkedIn URL
 · [**LinkedIn**](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)
-->

<sub>Open to feedback, ideas, and collaboration on backend and applied-AI projects.</sub>
