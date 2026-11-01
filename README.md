### LogStream ⚡

A lightweight, local API log visualization platform designed to transform raw terminal streams and unformatted server outputs into readable data tables. 

### Why I Built This

This tool was built out of frustration from debugging cryptic HTTP string payloads across terminal consoles during local development workflows. Enterprise logging software options were either too heavy or trapped behind subscription barriers. LogStream provides a free, zero-config framework to parse raw strings via optimized structural token fallbacks instantly. 

### Architecture & Framework Rules

* **Backend:** Flask/Python 3 engine running sequential regex engines to clean raw input strings.
* **Frontend:** Single-page asynchronous JavaScript execution mapped with functional Tailwind styles.
* **AI-Enhanced Workflow:** Developed components utilizing generative code scaffolding, while maintaining manual domain constraints to fix LLM string pattern edge vulnerabilities.
