![Banner](Images/BannerGitHub.png)

```c
/*
 * adiazmazzola.h
 *
 * Alvaro Arturo Diaz
 * Senior Data Engineer | FDE (Palantir Foundry)
 * Italy, remote | EU citizen
 */

#ifndef ADIAZMAZZOLA_H
#define ADIAZMAZZOLA_H

typedef struct {
    const char *role;
    const char *client;
    const char *domain;
    const char *scale;
    const char *since;
    const char *spoken[3];
} engineer_t;

static const engineer_t alvaro = {
    .role   = "Senior Data Engineer, Palantir Foundry consultant",
    .client = "Swiss Re, Finance Reporting & Analytics Engineering",
    .domain = "IFRS17 planning and reporting, 150+ users",
    .scale  = "7B records, end-to-end data products on Foundry",
    .since  = "2024-02",
    .spoken = { "es", "en", "it" },
};

#endif /* ADIAZMAZZOLA_H */
```

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

```c
/* every implementation has to satisfy both */
#define RULE_1 "quality data in, quality outcomes out"
#define RULE_2 "robust systems make mission-critical operations confident and repeatable"
```

```text
$ git log --format='%ad  %s' --date=format:%Y-%m
2024-02  Swiss Re (via Fincons Group / Esprimo): Sr. Data Engineer, Palantir Foundry
2021-09  Ministry of Production & Environment, AR: Dataflow IoT streaming, TensorFlow disease detection (93%)
2018-01  Diaz Mazzola Law Firm: lawyer, owner
```

## stack

| | |
|---|---|
| `lang`    | ![C](https://img.shields.io/badge/C-1c1917?style=flat-square&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/Python-1c1917?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1c1917?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-1c1917?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-1c1917?style=flat-square&logo=react&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-1c1917?style=flat-square&logo=gnubash&logoColor=white) |
| `data`    | ![PySpark](https://img.shields.io/badge/PySpark-1c1917?style=flat-square&logo=apachespark&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-1c1917?style=flat-square&logo=polars&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-1c1917?style=flat-square&logo=databricks&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-1c1917?style=flat-square&logo=pandas&logoColor=white) |
| `foundry` | ![Palantir Foundry](https://img.shields.io/badge/Palantir_Foundry-1c1917?style=flat-square&logo=palantir&logoColor=white) system design, Ontology, Workshop, Custom Widgets, Code Repositories, AIP Logic / Agents / Evals, Marketplace |
| `cloud`   | ![Azure](https://img.shields.io/badge/Azure_ADLS_Gen2-1c1917?style=flat-square) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-1c1917?style=flat-square&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-1c1917?style=flat-square&logo=googlebigquery&logoColor=white) Dataflow, Dataproc, Vertex AI |
| `ml`      | ![TensorFlow](https://img.shields.io/badge/TensorFlow-1c1917?style=flat-square&logo=tensorflow&logoColor=white) XGBoost, CatBoost, conformal prediction, MCP servers |
| `env`     | ![Linux](https://img.shields.io/badge/Linux-1c1917?style=flat-square&logo=linux&logoColor=white) ![Git](https://img.shields.io/badge/Git-1c1917?style=flat-square&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-1c1917?style=flat-square&logo=jupyter&logoColor=white) |
| `domain`  | IFRS17: BECF, reinsurance contracts, underwriting workflows, market mappings, rollforwards |

## activity

<p>
  <a href="https://github.com/adiazmazzola?tab=repositories"><img height="165" src="https://github-readme-stats.vercel.app/api?username=adiazmazzola&show_icons=true&include_all_commits=true&hide_rank=true&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=c9d1d9&icon_color=8b949e" alt="GitHub stats" /></a>
  <a href="https://github.com/adiazmazzola"><img height="165" src="https://streak-stats.demolab.com?user=adiazmazzola&hide_border=true&background=0d1117&stroke=30363d&ring=c9d1d9&fire=c9d1d9&currStreakNum=e6edf3&sideNums=e6edf3&currStreakLabel=c9d1d9&sideLabels=8b949e&dates=8b949e" alt="GitHub streak" /></a>
</p>

<!--START_SECTION:activity-->
```text
2026-10-07  push  adiazmazzola/adiazmazzola  main
```
<!--END_SECTION:activity-->

- [grapes-leaf-disease](https://github.com/adiazmazzola/grapes-leaf-disease): deep learning, leaf disease classification
- [dataScience](https://github.com/adiazmazzola/dataScience): data science notebooks

## contact

[adiazmazzola@gmail.com](mailto:adiazmazzola@gmail.com) · [LinkedIn](https://www.linkedin.com/in/alvaro-arturo-diaz-a2a4552a1/) · open to collaboration on data pipelines, Foundry, ML
