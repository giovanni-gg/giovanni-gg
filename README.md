### Hi, I'm Giovanni 👋

A few projects I've been building:

- **[ClipVault](https://github.com/giovanni-gg/ClipVault)** — Personal Windows clipboard manager (C# / WPF / .NET 8, SQLite). Clipboard history for text & images, pinning, folders, and a `Ctrl+Alt+V` quick panel.
- **[anki_swedish_creator](https://github.com/giovanni-gg/anki_swedish_creator)** — Python tool that generates AI text-to-speech audio and Anki-importable flashcard decks for language learning (ElevenLabs TTS + optional Gemini images).

### 🏢 Danish Endurance (private repos)

Data & software I've built for Danish Endurance, a multi-channel e-commerce company. These repos are private, so no links — but here's the architecture and the problem each one solves:

- **de-dbt** — Company-wide analytics engineering. A **dbt + BigQuery** data warehouse (500+ models) on a 4-layer medallion architecture, unifying **30+ data sources** — Shopify, Amazon (EU/NA/JP), marketplaces (Bol, Zalando, Allegro, Decathlon, Boozt…), ad platforms (Amazon/Google/Meta/Microsoft Ads), Klaviyo, GA4 and Business Central — into governed sales, advertising, inventory, finance and customer models that power BI across the business. *(390+ merged PRs authored, of 970+ in the repo.)*
- **amz_deal_planning** — Internal web app for planning Amazon promotions: scheduling product-type packs into ISO weeks and pricing deals at child-ASIN level. **Next.js 16 (App Router) · React 19 · TypeScript · Drizzle ORM on Neon Postgres · deployed on Vercel.**
- **packaging-stickers-approval-software** — AI-assisted QA tool that checks packaging-sticker PDFs against official EAN/composition master data. Renders each PDF page and extracts fields via the **Claude API**, then diffs them against data kept fresh by nightly crons (Delogue API + BigQuery). **Next.js 16 on Vercel, Vercel Blob storage, no database.**
- **AI_translator** — Product-localization tool that translates Excel listing content into 9 languages using a **dictionary-first + LLM-fallback** strategy for consistency, cost control and strict character-limit compliance. **Python / Streamlit + OpenAI**, containerized on **Google Cloud Run**, with BERTScore-based quality evaluation.
- **ai-visibility-tracker** — Monitors how the brand and its products surface in AI-assistant answers ("generative engine optimization"). Runs curated prompt sets across **OpenAI and Google Gemini**, captures and scores the responses, and lands results in **BigQuery** for dashboards. **Python, Dockerized on Google Cloud (Cloud Build).**

### 📦 Archive

Older projects and coursework:

- **[busines-nl2sql](https://github.com/giovanni-gg/busines-nl2sql)** — Natural-language-to-SQL for business data.
- **[master_thesis](https://github.com/giovanni-gg/master_thesis)** — Master's thesis.
- **[text-to-sql-thesis](https://github.com/giovanni-gg/text-to-sql-thesis)** — Text-to-SQL research.
- **[musical-life-alercio](https://github.com/giovanni-gg/musical-life-alercio)** — A project about my father's musical life.
- **[mbml_project](https://github.com/giovanni-gg/mbml_project)** — Model-Based Machine Learning project.
- **[G16_SocialGraphs](https://github.com/giovanni-gg/G16_SocialGraphs)** — Social Graphs course project (DTU 02805).
- **[socialgraphs-MetacriticProject](https://github.com/giovanni-gg/socialgraphs-MetacriticProject)** — Social Graphs analysis of Metacritic data.
- **[socialgraphs_ass2](https://github.com/giovanni-gg/socialgraphs_ass2)** — Social Graphs assignment.
- **[RoboRallyInspiration](https://github.com/giovanni-gg/RoboRallyInspiration)** — RoboRally project materials.
- **[RoboRally](https://github.com/giovanni-gg/RoboRally)** — Object-oriented software development course project (DTU 02160).
