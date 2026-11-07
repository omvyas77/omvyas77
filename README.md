# Om Hitesh Vyas

I build data and ML systems end to end: pipelines, models, evaluations, and the apps people use them through. Each project below says what its results show and what they don't. M.S. in Information Management, University of Illinois, 2026.

**Selected work**
- [finhelm](https://github.com/omvyas77/finhelm): question answering over bank SEC filings that cites its sources or refuses. It finds the evidence for 74% of questions and refuses 18 of the 19 it can't answer, at $0.03 a question. RAG, FAISS, CI-gated evals, Docker. [Demo](https://huggingface.co/spaces/omvyas77/finhelm)
- [uplift](https://github.com/omvyas77/uplift): a 14M-record randomized experiment used as the answer key for causal methods. About 92,000 of the treated arm's 577,000 visits were caused by the campaign, and inverse-propensity weighting on the randomized data biased the estimate by −91% while every overlap check looked healthy. dbt, DuckDB, EconML, FastAPI, Dagster. [Dashboard](https://huggingface.co/spaces/omvyas77/uplift)
- [program-health](https://github.com/omvyas77/program-health): a pipeline over seven public sources that refreshes on a schedule, tests every build, and publishes an app, dashboards, and a brief. It found that online programs account for 4,781 of the 4,940 students a business school added since 2017. dbt, DuckDB, GitHub Actions, Streamlit, Tableau. [App](https://huggingface.co/spaces/omvyas77/gies-program-health) · [Brief](https://github.com/omvyas77/program-health/blob/main/brief/brief.pdf)
- [Credit-risk-early-signals](https://github.com/omvyas77/Credit-risk-early-signals): early-warning NLP on 680,000 consumer complaint narratives. LightGBM on TF-IDF features reaches a PR-AUC of 0.31 where 0.7% of complaints are flagged; a fine-tuned transformer reached 0.12.

**Research**
- F-Transformer: A Federated Transformer for Efficient and Privacy-Preserving Sequence Generation, *Scientific Reports*, 2026. [Paper]([(https://doi.org/10.1038/s41598-026-40881-0)) · [Code](https://github.com/omvyas77/Efficient-Sequence-Generator-)
- BookNest: Ensemble-Based Book Recommendation System, IC4S'05. [Code](https://github.com/omvyas77/BookNest-Ensemle-based-Book-Recommendation-System)

**Tools I use most:** SQL, Python, dbt, DuckDB, Postgres · scikit-learn, LightGBM, PyTorch, Hugging Face · FastAPI, Streamlit, Docker, GitHub Actions

[LinkedIn](https://www.linkedin.com/in/om-hitesh-vyas-97340a204/) · omvyas288@gmail.com
