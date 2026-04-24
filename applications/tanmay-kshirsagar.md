# Application: Tanmay Kshirsagar

---

## meta

| | |
|---|---|
| **name** | Tanmay Kshirsagar |
| **location** | Latur, Maharashtra · ready to relocate to Pune immediately |
| **portfolio** | [tanmayportfolio.ccbp.tech](https://tanmayportfolio.ccbp.tech) |
| **github** | [@Tanmay1112004](https://github.com/Tanmay1112004) |
| **linkedin** | [tanmay-kshirsagar](https://www.linkedin.com/in/tanmay-kshirsagar) |
| **email** | tanmaykshirsagar001@gmail.com |

---

## one thing I shipped

**EDA Automation with LLM** — I built a tool that takes any raw dataset and runs a full exploratory data analysis automatically, using Mistral LLM via Ollama to generate human-readable insights on top of the statistical output. The interface is a Gradio app — drag in a CSV, get a narrative breakdown of your data's shape, outliers, correlations, and anomalies in plain English.

The real challenge wasn't the ML — it was prompting the model to produce genuinely useful analysis instead of generic summaries. I iterated on the system prompt ~40 times before the outputs felt trustworthy.

What I'd do differently: the UI is functional but blunt. I'd redesign it so the insights are layered — a quick "what matters" summary first, with drill-down sections for users who want the numbers.

→ [github.com/Tanmay1112004](https://github.com/Tanmay1112004)

---

## tools I reach for

**Daily:** Figma, Claude

**Also in the stack:** Python, React, LangChain, Gemini API, n8n, Gradio, Streamlit

I use Claude as a thinking partner, not an autocomplete — I'll paste in a design decision I'm stuck on and work through it in conversation before touching Figma.

---

## why amber · one thing I'd redesign

**The search results page has no memory, and that's expensive.**

I went through the London listings flow. 220 properties. Filters for budget, room type, move-in month. Standard stuff. But every time you come back — new session, same blank slate. No "you looked at ensuites under £300 last time." No "students from your university usually shortlist these three." The platform collects massive behavioural signal and surfaces none of it back to the user.

The specific gap: the filter panel resets on every visit, room type labels are inconsistent across listings ("Classic Ensuite" vs "Bronze Ensuite" vs "Gold Studio" — students don't know what tier they're in), and there's no indication of *why* a listing appears first.

What I'd explore: a persistent preference layer — lightweight, maybe just localStorage to start — that remembers your last filter state and surfaces a "back where you left off" strip at the top on return visits. Pair that with consistent room-tier labelling (a small taxonomy problem with a big trust payoff), and the search page goes from a catalogue to something that feels like it knows you're in a hurry.

This isn't a moonshot. It's a week of design work and a sprint of engineering. The harder question is whether the team wants to own that state or push it into an account wall — that tradeoff is the interesting design decision.

---

## one question for the team

The role mentions "generative UI and new interaction patterns" — are there specific flows on the product where you're actively experimenting with AI-generated UI right now, or is that still at the exploration stage? I'm asking because the answer changes what kind of intern would be most useful: someone who ships polished screens fast, or someone who breaks things interestingly.

---
