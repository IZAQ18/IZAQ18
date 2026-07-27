<div align="center">

# Ahsan QaZi

### AI/ML Engineer

**I build event-driven equity research pipelines and multi-LLM systems.**

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahsan-maqbool-ahmad-6016a1367)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ahsan_qazi_)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahsanmaqboolahmad1811@gmail.com)

</div>

<br>

## 🎯 What I work on

Most of my work sits at one specific seam: **a stock moves sharply, and something caused it.**

Turning that into data means scraping minute bars, detecting the move statistically, finding the filing or news article responsible, and proving the link is causal rather than coincidental — at scale, with every row accounted for.

```mermaid
flowchart LR
    A[Polygon<br/>5-min bars] --> B[Spike / crash<br/>detection]
    B --> C[Causal news<br/>matching]
    D[SEC EDGAR<br/>filings] --> E[Feature<br/>extraction]
    C --> F[(PostgreSQL)]
    E --> F
    F --> G[Labeled<br/>event dataset]

    style A fill:#1f6feb,stroke:#58a6ff,color:#fff
    style D fill:#1f6feb,stroke:#58a6ff,color:#fff
    style B fill:#238636,stroke:#3fb950,color:#fff
    style C fill:#238636,stroke:#3fb950,color:#fff
    style E fill:#238636,stroke:#3fb950,color:#fff
    style F fill:#8957e5,stroke:#a371f7,color:#fff
    style G fill:#bb8009,stroke:#d29922,color:#fff
```

<table>
<tr>
<td width="33%" valign="top">

### 📈 Market microstructure

Robust modified z-score detection (median/MAD) over 5-min bars across ~100 tickers, with a dual statistical **and** economic gate so thresholds stay defensible.

</td>
<td width="33%" valign="top">

### 📄 Filing intelligence

SEC EDGAR filings parsed into per-filing feature rows — filing-native extraction, XBRL, and source cross-validation against a news lookback window.

</td>
<td width="33%" valign="top">

### 🤖 Multi-LLM systems

A three-seat LLM council that labels financial news against a versioned rubric, with an explicit decision layer for when the seats disagree.

</td>
</tr>
</table>

<br>

## 🛠️ Tech stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)

**Data & ML**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**AI / LLM**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Web**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

**Tools & APIs**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Polygon.io](https://img.shields.io/badge/Polygon.io-5D5FEF?style=for-the-badge&logoColor=white)
![SEC EDGAR](https://img.shields.io/badge/SEC%20EDGAR-1A3D6D?style=for-the-badge&logoColor=white)
![Chrome](https://img.shields.io/badge/Chrome%20MV3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

</div>

<br>

## ⭐ Featured

<div align="center">

### [Oracruit](https://github.com/IZAQ18/Oracruit) — Smart Prep for Smart Careers

</div>

An AI-powered mock interview platform. Pick a role, seniority, and tech stack; it generates a tailored question set, runs the interview as a **real-time voice conversation**, then grades the transcript under a Zod schema so feedback comes back as validated structured scores instead of free-form prose.

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js%2016-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

</div>

> My quantitative pipeline work — spike/crash detection, causal news matching, SEC feature extraction, and the multi-LLM labeling council — currently lives in private repositories. Happy to walk through the architecture and code on request.

<br>

## 🧭 How I build

|  | Principle |
|---|---|
| 📋 | **Statuses over silence.** Every unmatched row gets an explicit status and reason. Nothing is dropped, nothing is forced into a match it doesn't deserve. |
| ⚙️ | **Deterministic rules over LLM judgment** wherever a rule can do the job. Models handle the residual, and their disagreement is itself data. |
| 🎛️ | **Tunables in one place.** Every threshold lives in a single config, never inline. |
| 📐 | **Robust statistics by default.** Median and MAD over mean and σ — because one outlier shouldn't mask the next. |
| 📝 | **Decisions get written down** as they're made, not reconstructed afterward. |

<br>

<div align="center">

### Let's talk

If you're working on market data, event detection, or LLM evaluation systems — I'd like to hear about it.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahsan-maqbool-ahmad-6016a1367)

</div>
