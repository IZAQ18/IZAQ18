# Ahsan QaZi

**I build event-driven equity research pipelines and multi-LLM labeling systems.**

Most of my work sits at one specific seam: a stock moves sharply, and something
caused it. Turning that into data means scraping minute bars, detecting the move
statistically, finding the filing or news article responsible, and proving the
link is causal rather than coincidental — at scale, with every row accounted for.

---

### What I'm working on

**Market microstructure → labeled events**
Polygon 5-min bars across ~100 tickers, robust-z spike/crash detection with
session-relative windowing, and a deterministic rule matcher that ties each event
to the SEC filing or news article that caused it.

**SEC filing feature extraction**
EDGAR filings parsed into per-filing feature rows — filing-native extraction with
source cross-validation, joined against news within a lookback window.

**Multi-LLM labeling**
A 3-seat LLM council that classifies financial news against a versioned rubric,
with an explicit decision layer for disagreement. Plus a Chrome extension that
fans one paste out to four chat models and reads the replies side by side.

---

### Principles I actually build by

- **Statuses over silence.** Every unmatched row gets an explicit status and
  reason. Nothing is dropped, nothing is forced into a match it doesn't deserve.
- **Deterministic rules over LLM judgment** wherever a rule can do the job.
  LLMs are for the residual, and their disagreement is data.
- **Tunables in one place.** Every threshold lives in `config.py`, never inline.
- **Decisions get written down.** Design rulings are documented as they're made,
  not reconstructed afterward.

---

### Stack

`Python` `pandas` `PostgreSQL` `SEC EDGAR` `Polygon.io`
`TypeScript` `Next.js` `Firebase` `Chrome MV3`
`Groq` `Gemini` `Claude`

---

### Reach me

[LinkedIn](https://linkedin.com/in/ahsan-maqbool-ahmad-6016a1367)
