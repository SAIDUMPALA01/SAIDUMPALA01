### Hi, I'm Sai 👋

**AI/ML engineer in London. I build LLM applications and the evaluations that show whether they work.**

- 🎓 MSc Computer Science, Birmingham City University (2025)
- 📄 Published research on evaluating LLM output: [*A Practical Six-Dimension Evaluation Framework*](https://doi.org/10.5281/zenodo.20102941) (Zenodo, 2026)
- 🧪 Freelance LLM evaluation for AI labs via Mercor and Outlier: reviewing model outputs and code against detailed quality standards
- 🔎 Open to **junior AI / LLM / ML engineer** and **Python engineer** roles in London (hybrid or on-site)

---

#### What I've built

| Project | What it shows |
|---|---|
| [**docs-rag-eval**](https://github.com/SAIDUMPALA01/docs-rag-eval) | RAG over documentation with citations and "I don't know" answers, measured on 48 labelled questions (Hit@5 0.95, MRR 0.73 for BM25). BM25 written from scratch, hybrid retrieval, CI quality gate |
| [**sixdim-eval**](https://github.com/SAIDUMPALA01/LLm-Evaluation-framework) | My paper as a pip-installable library: LLM-as-judge on six dimensions, judge-vs-human agreement (kappa, TPR/TNR), and a GitHub Action that fails CI when output quality drops |
| [**ResuMetric**](https://github.com/SAIDUMPALA01/resumetric) | A deployed FastAPI service that catches fabricated content in AI-written CVs. Web UI, judge-consistency mode, rate limiting, tracing, Docker, [live demo](https://saidumpala-resumetric.hf.space) |
| [**uk-visa-sponsor-mcp**](https://github.com/SAIDUMPALA01/uk-visa-sponsor-mcp) | An MCP server that lets Claude or any MCP client search the UK sponsor register and check Skilled Worker salary rules. Tested over a real stdio session |
| [**pneumonia CNN**](https://github.com/SAIDUMPALA01/medical-image-classification-system1) | My MSc project, rebuilt after I audited my own results: patient-level splits, sensitivity-first evaluation, Grad-CAM, an API |

#### Tools I use in these projects

`Python` · `FastAPI` · `Pydantic` · `pytest` · `Anthropic API` · `RAG` · `BM25 / TF-IDF / embeddings` · `MCP` · `LLM evaluation` · `TensorFlow / Keras` · `scikit-learn` · `Docker` · `GitHub Actions` · `SQL`

#### How I work

I treat evaluation as part of the product. Every project above has tests that run without API keys, and anything that uses a model reports how well it works, including where it fails.

📫 [LinkedIn](https://www.linkedin.com/in/sai-dumpala) · [ORCID](https://orcid.org/0009-0001-0260-0072) · dumpalasairamkrishnareddy@gmail.com
