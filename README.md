![Banner](Images/BannerGitHub.png)

## Alvaro Arturo Diaz

**Senior Data Engineer | FDE (Palantir Foundry)**\
Swiss Re, Finance Reporting & Analytics Engineering, since 2024. IFRS17 planning and reporting, 150+ users.\
End-to-end data products on Foundry, 7B-record scale. Italy, remote. EU citizen. ES / EN / IT.

## numbers

| what                                               | before    | after     |
|----------------------------------------------------|----------:|----------:|
| cash-flow records, nested to array-of-struct       | 600M rows | 600K rows |
| unmapped reference-data records (of 6.5M)          | 11,000    | 150       |
| ~20M-record planning pipeline runtime              | 60 min    | 45 min    |

Nested rows are expanded on demand in the UI. No record-level detail lost.

## work

- Data-intensive processing: joins and aggregations over 7B records.
- System design on Foundry: end-to-end data products, from ingestion and pipelines through ontology and functions to custom front ends.
- Cash-flow adjustment app, built from scratch. React custom widgets, Python functions for near-real-time edits, Polars and PySpark for bulk loads. Sources: ADLS Gen2, Databricks.
- Foundry to ADLS Gen2 integration. Service-principal auth, POSIX ACLs.
- Ontology: fragmented models merged into one shared repo with single-source property definitions. DEV / NON-PROD / PROD promotion.
- Two AIP agents: one runs Action Types in a scenario-planning app, one speeds up manual record corrections. Both fall back to deterministic logic on edge cases.
- L3 production support. Direct line to business owners and IT module owners.
- I take vague business specs, find the actual pain point and turn it into executable work.

**Every implementation has to answer yes to both:**
1. Does it add business value?
2. Does it make the process easier, more efficient and more robust?

Only then does it go to the client or end user.

## history

| since   | where                                    | what                                                                                                      |
|---------|------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| 2024-02 | Swiss Re (via Fincons Group / Esprimo)   | Sr. Data Engineer, Palantir Foundry                                                                       |
| 2021-09 | Ministry of Production & Environment, AR | Dataflow IoT streaming, TensorFlow disease detection (93%)                                                |
| 2018-01 | Diaz Mazzola Law Firm                    | Lawyer, owner                                                                                             |
| 2017-10 | Hospital Eleazar Herrera Motta           | Administrative Director. Digitized admin, patient intake, billing and statistics: 5x operational efficiency |

## stack

| | |
|---|---|
| `lang`    | ![C](https://img.shields.io/badge/C-1c1917?style=flat-square&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/Python-1c1917?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1c1917?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-1c1917?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-1c1917?style=flat-square&logo=react&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-1c1917?style=flat-square&logo=gnubash&logoColor=white) |
| `data`    | ![PySpark](https://img.shields.io/badge/PySpark-1c1917?style=flat-square&logo=apachespark&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-1c1917?style=flat-square&logo=polars&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-1c1917?style=flat-square&logo=databricks&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-1c1917?style=flat-square&logo=pandas&logoColor=white) |
| `Palantir Foundry` | ![Ontology Design](https://img.shields.io/badge/Ontology_Design-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Spaces](https://img.shields.io/badge/Spaces-1c1917?style=flat-square&logo=palantir&logoColor=white) ![AIP Chatbot Studio](https://img.shields.io/badge/AIP_Chatbot_Studio-1c1917?style=flat-square&logo=palantir&logoColor=white) ![AIP Logic](https://img.shields.io/badge/AIP_Logic-1c1917?style=flat-square&logo=palantir&logoColor=white) ![AI FDE Agentic Development Lifecycle](https://img.shields.io/badge/AI_FDE_Agentic_Development_Lifecycle-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Workshop](https://img.shields.io/badge/Workshop-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Workflow Lineage](https://img.shields.io/badge/Workflow_Lineage-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Code Repositories](https://img.shields.io/badge/Code_Repositories-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Custom Widgets](https://img.shields.io/badge/Custom_Widgets-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Contour](https://img.shields.io/badge/Contour-1c1917?style=flat-square&logo=palantir&logoColor=white) ![Quiver](https://img.shields.io/badge/Quiver-1c1917?style=flat-square&logo=palantir&logoColor=white) |
| `cloud`   | ![Azure ADLS Gen2](https://img.shields.io/badge/Azure_ADLS_Gen2-1c1917?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB2aWV3Qm94PSIwIDAgMTI4IDEyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNNDMuOTgzIDQuNjUzYTUuOTExIDUuOTExIDAgMDE1LjYgNC4wMjJsMzUuOTEgMTA2LjM5NmE1LjkxMSA1LjkxMSAwIDAxLTUuNjAzIDcuODAyaDQxLjM4YTUuOTE3IDUuOTE3IDAgMDA0LjgtMi40NjUgNS45MDkgNS45MDkgMCAwMC43OTgtNS4zNEw5MC45NjEgOC42NzJhNS45MSA1LjkxIDAgMDAtNS42MDItNC4wMjJ6bS0xLjMzNi40NzhhNS45MiA1LjkyIDAgMDAtNS42MSA0LjAyOUwxLjEzMiAxMTUuNTVhNS45MSA1LjkxIDAgMDA1LjYgNy44aDI4Ljg5M2MxLjIzOSAwIDIuNDQ2LS40MSAzLjQ1Mi0xLjExM2E1LjkyMyA1LjkyMyAwIDAwMi4xNTctMi45MTZsNy4wMTktMjAuNzEtMTMuNDExLTEyLjg1N2MtLjI0Ni0uMjczLTEuMzUzLTIuMjc0LS4zNjktNC4wMDIgMS4xMDgtMS42NTkgMi45NTUtMS42NTkgMi45NTUtMS42NTloMTcuMjg1bDkuMDc0LTI2LjE0NUw0OC4yNzQgOC4zMjFjLS4wNDItLjIwNS0uOTE0LTEuMzY1LTIuMjgxLTIuMjgtMS4zNy0uOTE1LTMuMzQ1LS45MDktMy4zNDUtLjkwOXptLTQuODggNzUuNzRhMi43MjQgMi43MjQgMCAwMC0xLjg2IDQuNzE4bDM3LjgzIDM1LjMxYzEuMTAxIDEuMDMgMi41MDIgMS42MzEgNC4wMDcgMS42MzEgMCAwIDEuMjgyLjA2OCAyLjA1NS0uMDMzIDEuODE3LS4yNzMgMy41MjUtMS43NjggNC4wOS0yLjM5IDEuNDU3LTEuOTM5Ljc5NC00Ljk1Ljc5NC00Ljk1bC0xMS40NS0zNC4yOHoiIGZpbGw9IiNmZmZmZmYiLz48L3N2Zz4K&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-1c1917?style=flat-square&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-1c1917?style=flat-square&logo=googlebigquery&logoColor=white) ![Dataflow](https://img.shields.io/badge/Dataflow-1c1917?style=flat-square&logo=googledataflow&logoColor=white) ![Dataproc](https://img.shields.io/badge/Dataproc-1c1917?style=flat-square&logo=googledataproc&logoColor=white) ![Vertex AI](https://img.shields.io/badge/Vertex_AI-1c1917?style=flat-square&logo=googlecloud&logoColor=white) |
| `ml`      | ![TensorFlow](https://img.shields.io/badge/TensorFlow-1c1917?style=flat-square&logo=tensorflow&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-1c1917?style=flat-square) ![CatBoost](https://img.shields.io/badge/CatBoost-1c1917?style=flat-square) ![Conformal Prediction](https://img.shields.io/badge/Conformal_Prediction-1c1917?style=flat-square) ![MCP Servers](https://img.shields.io/badge/MCP_Servers-1c1917?style=flat-square&logo=modelcontextprotocol&logoColor=white) |
| `env`     | ![Linux](https://img.shields.io/badge/Linux-1c1917?style=flat-square&logo=linux&logoColor=white) ![Git](https://img.shields.io/badge/Git-1c1917?style=flat-square&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-1c1917?style=flat-square&logo=jupyter&logoColor=white) |
| `domain`  | ![IFRS17](https://img.shields.io/badge/IFRS17-1c1917?style=flat-square) ![BECF](https://img.shields.io/badge/BECF-1c1917?style=flat-square) ![Reinsurance Contracts](https://img.shields.io/badge/Reinsurance_Contracts-1c1917?style=flat-square) ![Underwriting Workflows](https://img.shields.io/badge/Underwriting_Workflows-1c1917?style=flat-square) ![Market Mappings](https://img.shields.io/badge/Market_Mappings-1c1917?style=flat-square) ![Rollforwards](https://img.shields.io/badge/Rollforwards-1c1917?style=flat-square) |

## contact

[adiazmazzola@gmail.com](mailto:adiazmazzola@gmail.com) · [LinkedIn](https://www.linkedin.com/in/alvaro-arturo-diaz-a2a4552a1/) · open to collaboration on data pipelines, Foundry, ML
