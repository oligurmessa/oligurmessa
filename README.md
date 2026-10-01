### hi, I'm Oli

CS and math undergrad at the University of St. Thomas (B.S. Computer Science, B.A. Mathematics, graduating Dec 2026). I do applied machine learning research and build data systems that keep working after I stop looking at them.

**Research**

- **Diffusion model probing** (StabilityAI, 2025–present, in progress) — how much image quality do you lose when you cut inference steps? Evaluation harness over 1,600 prompts × 27 step configurations with fixed seeds, scored with PickScore. Early result: 5–10% less compute at PickScore 0.90–0.95.
- **AI audio for user-generated game content** (UST Computer Science, 2024) — text-to-audio and image-to-audio pipelines so player-built levels get their own sound, using MusicGen and AudioGen at ~4 s per clip. Co-author on [arXiv:2404.17018](https://arxiv.org/abs/2404.17018).
- **GeezNet** (UST Undergraduate Research Opportunities Program, 2023) — CNN, ResNet50 and InceptionV3 baselines for handwritten Ge'ez numerals on a 10,000-image dataset, with augmentation and regularization ablations and error analysis of confusable digit pairs. 97.8% accuracy. First author, published at IEEE AIBThings 2025: [doi:10.1109/AIBThings66987.2025.11296233](https://doi.org/10.1109/AIBThings66987.2025.11296233).

**Projects**

- [nyc311-pipeline](https://github.com/oligurmessa/nyc311-pipeline) — incremental pipeline on NYC's live 311 feed. Socrata → parquet → DuckDB → dbt → Dagster → Streamlit. Runs itself every 6 hours on GitHub Actions and fails loudly when the data is late, duplicated, or wrong.
- [viral-to-value](https://github.com/oligurmessa/viral-to-value) — do viral Instagram campaigns bring customers who stay? Cohorts, contribution-margin LTV, LTV:CAC, hypothesis tests. Short answer: saves beat shares.
- [drowsiness-numpy](https://github.com/oligurmessa/drowsiness-numpy) — eye-state classifier in plain NumPy with hand-derived backprop, evaluated per subject so it can't cheat.
- [hallpals](https://github.com/oligurmessa/hallpals) — duty and incident platform for resident advisors with role-based access. Piloted with 10 RAs in one hall.
- [finitycrew](https://github.com/oligurmessa/finitycrew) — rotating savings groups, the Ethiopian Equb, as a web app.
- [mini-pentest-toolkit](https://github.com/oligurmessa/mini-pentest-toolkit) — bounded recon and offline analysis for learning security, with reports.

**Tools I reach for**

Python · PyTorch · TensorFlow/Keras · scikit-learn · NumPy / pandas · OpenCV · SQL · dbt · DuckDB · Dagster · Docker · GCP · Java · C++ · TypeScript

Looking for data, AI, ML roles starting 2027. Email is on the profile, or [LinkedIn](https://linkedin.com/in/oligurmessa).
