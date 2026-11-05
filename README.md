# Pruthvi M Javali

Data engineer in Bengaluru who likes building with AI. I've spent three years on compliance and regulatory data at JPMorgan Chase and LSEG. Outside work I build my own tools with Claude Code, and I write down how each one really went, including the one I killed.

[![Portfolio](https://img.shields.io/badge/-Portfolio-1F3FD6?style=flat-square&logo=googlechrome&logoColor=white)](https://pruthvi-mocha.vercel.app) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pruthvimjavali/) [![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:pruthvi182001@gmail.com)

## What I've built

- **[JobHunter](https://pruthvi-mocha.vercel.app/#jobhunter):** a job search run as a data pipeline. It collects postings from 61 company career sites, scores the fit, and has an LLM write a resume that code checks for invented numbers and skills. A Chrome extension fills the form and never presses Submit.
- **[Aaroh](https://getaaroh.in/):** the resume service JobHunter turned into, live now. Its [free check](https://getaaroh.in/check/) reads a PDF or Word resume in the browser, so the file never leaves the device. Payments aren't open yet, so it's pre-revenue.
- **[Agent Lab](https://github.com/Pruth18/agent-lab):** one agent job built as a plain Python loop, a LangGraph agent and a CrewAI crew, all marked by the same validator. They all reached clean answers, but CrewAI used about 5 times the tokens of LangGraph.
- **[WaChat](https://pruthvi-mocha.vercel.app/#wachat):** WhatsApp booking for clinics, built so its own database can't read the chats. Sessions are AES-256-GCM encrypted, and replying DELETE destroys the key. 62 tests pass, with no clinic live yet.
- **[Fair Value Gaps on NSE](https://pruthvi-mocha.vercel.app/#fvg):** a popular trading rule, tested overnight by parallel AI agents: 16,989 strategy variants on 10 years of data. 0 of 3 pre-registered tests passed, so I killed it. Historical research, not investment advice.
- **[GeoWake](https://github.com/Pruth18/GeoWake):** an Android alarm that rings when you reach a place, not at a time. No account, no server, and nothing leaves the phone. 232 tests pass, and a real commute is the next test.
- **[Customer churn prediction](https://github.com/Pruth18/Churn_Prediction):** XGBoost at 85% accuracy, with SHAP for the top 5 drivers and dashboards in Streamlit.

## At work

- **JPMorgan Chase, Data Management Analyst** (Dec 2025 to now): KYC and AML reporting. Removed about 4 hours of weekly rework by fixing a late report at its source, and ran Copilot training for my whole team.
- **London Stock Exchange Group, Software Engineer** (Aug 2023 to Dec 2025): pipelines for regulatory reporting. Reached 99.9% validation accuracy across 2 legacy migrations, and prevented 90% of SLA-breaching failures with alerts on 6 critical jobs.

## What I use

- **AI:** Claude Code (skills, subagents, MCP), Claude and Gemini APIs, custom agent loops and evals. Learning projects with LangGraph, LangChain, CrewAI and Hugging Face.
- **Data:** Python, SQL, PySpark, Azure Data Factory, Databricks, Delta Lake.
- **Everything else:** Flask, Astro, React Native, Docker, Git.

Most of my work is in private repos. [See it running on my portfolio](https://pruthvi-mocha.vercel.app), or ask me for a walkthrough.
