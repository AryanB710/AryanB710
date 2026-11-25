# Hi, I'm Aryan Bose

Final-year Computer Science student at MITE, Mangalore. I build LLM systems I can measure: RAG that cites its sources or abstains, eval gates that block bad changes in CI, and research on catching hallucinated code before it ships.

**Open to:** GenAI / AI Engineering / Software Development internships · Bangalore or remote · available from mid-December 2026

[Portfolio](https://aryan-bose-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/aryan-bose-b73960227/) · [Email](mailto:aryanbose.710@gmail.com)

---

## Featured projects

**[Ask My Docs](https://github.com/AryanB710/ask-my-docs)**: production-style RAG with an eval gate
Answers questions over a document set, and every sentence has to cite its source or the system abstains. Hybrid retrieval (BM25 + vectors) with reranking, tracing on every request, and a CI eval gate that blocks merges that make answers worse.
`Python` `Docker` `GitHub Actions`

**[SAFE-Loop](https://github.com/AryanB710/safe-loop)** (research): feedback loop for LLM-generated code
Runs static analysis and hallucination detection on code an LLM writes, then feeds the findings back to the model. I built the benchmark dataset (7 error categories) and ran experiments with Qwen2.5-Coder 7B and 14B through Ollama at 0, 3 and 6 feedback rounds. <!-- ADD ONE HEADLINE RESULT, e.g. "pass rate went from X% to Y% after 3 rounds" -->
`Python` `Ollama` `Docker`

**[EvalTrack](https://github.com/AryanB710/evaltrack)** (in progress): LLM prompt evaluation and regression testing
Runs a suite of test prompts against an LLM app, scores the outputs, and flags regressions between prompt or model versions.
`Python` <!-- ADD STACK -->

**[Location Recommendation System](https://github.com/AryanB710/location-recommender)**: shooting locations for content creators
Takes a text brief for a shoot and recommends real locations: BERT matches the brief to place descriptions, Google Places supplies candidates, and OpenWeather checks conditions.
`Python` `BERT` `Flask` `MongoDB`

**[Payment Reconciliation & Exception Tracker](https://github.com/AryanB710/payment-reconciliation-tracker)** (in progress)
Matches payment records across sources and surfaces mismatches for review. <!-- EDIT TO MATCH WHAT IT ACTUALLY DOES + STACK -->

**[Portfolio](https://github.com/AryanB710/portfolio)**: [live site](https://aryan-bose-portfolio.vercel.app/)
3D portfolio built with React, TypeScript, Three.js and GSAP, deployed on Vercel.

---

## Research & certifications

- Paper accepted at **AICCoNS 2027**: *<!-- PAPER TITLE -->*
- Machine Learning Specialization and Generative AI for Software Development (DeepLearning.AI)
- Introduction to Machine Learning (Google Developers)
- NPTEL Introduction to Virtual Reality: Silver (80%)

## Tech I work with

**Languages:** Python, Java, JavaScript / TypeScript, SQL
**AI / ML:** LLMs (Ollama, Qwen2.5-Coder), RAG, BM25 + vector retrieval, reranking, BERT, LLM evaluation
**Backend & data:** Flask, MongoDB, MySQL
**Frontend:** React, Three.js, HTML, CSS
**Tools:** Docker, Git, GitHub Actions, Tableau, Figma
