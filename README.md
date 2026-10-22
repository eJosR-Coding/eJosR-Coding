# Joseph Rodriguez

**Full-stack Engineer · Backend and LLM Integrations**
Lima, Peru

Currently: building [FourLayer](https://fourlayer.dev), a visual C4 editor, now in public beta.

---

### Work

**[FourLayer](https://fourlayer.dev)** · `private repo`
Architecture diagrams drift because every view is drawn by hand. FourLayer keeps one semantic C4 model and renders Context, Container, Component and Deployment views from it. It imports and exports Mermaid and Structurizr DSL, exports PNG and SVG, and supports Google sign-in with private cloud workspaces (Supabase) and owner / editor / viewer sharing.

**[GitBell](https://github.com/eJosR-Coding/gitbell)** · `Tauri 2` `Rust` `TypeScript`
GitHub activity is easy to miss when coding agents commit and open PRs for you. GitBell is a tray app that sends native desktop notifications on Linux and Windows. It polls with ETags to stay within API limits, keeps the token in the OS keyring, and flags commits and PRs from coding agents by trailers, bot logins and branch prefixes. `gitbell notify` lets scripts and agents send their own notifications. UI in English and Spanish. [v0.3.0](https://github.com/eJosR-Coding/gitbell/releases/latest) adds signed auto-updates; installers for Linux (deb, rpm, AppImage) and Windows.

**[Aura Audit](https://aura.fourlayer.dev)** · `Next.js` `FastAPI` · `private repo`
Enter a GitHub username and get a timed, captioned replay of the profile plus a shareable verdict. The score comes from deterministic rules, not from a model.

**[LoL RAG Chatbot](https://github.com/eJosR-Coding/lol-chatbot)** · `FastAPI` `sentence-transformers` `Astro` `Evaluation`
University course project (UNAB, 2026). Hybrid retrieval (multilingual embeddings plus lexical matching) over a 239-term glossary, a gate that refuses below a similarity threshold without calling any model, and answers shown with their source entry. Measured on dev, held-out and fresh question sets: in-glossary accuracy went from 6/15 to 12/15 on dev and from 6/10 to 7/10 on the fresh set. A local LLM rewrite exists but is opt-in, because it changed meaning too often.

Also:
- [Translator Runner](https://github.com/eJosR-Coding/translator-runner): KRunner plugin for KDE Plasma 6 that translates text from the launcher through translate-shell (online), plus local text transforms.
- [GuardyMed](https://github.com/eJosR-Coding/GuardyMed): hospital guard scheduling, worker requests and face-verified attendance (FastAPI, Vue 3, InsightFace). Face verification evaluated on 1,000 LFW pairs (AUC 0.981; thresholds tuned on the same data); runs on a labelled simulated stub by default.

---

### Experience

**Valere**: sole engineer on a RAG chatbot for Peruvian tax questions (AWS Bedrock, pgvector). Accuracy on expert-labeled questions went from 60% to 92%.

---

[Portfolio](https://ejosr-coding.github.io/portfolio-ejos/) · [LinkedIn](https://linkedin.com/in/ejosrodriguez) · [X](https://x.com/neolimenodev)
