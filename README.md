<h1 align="center">R Analytics Skill</h1>

<p align="center">
  <strong>Comprehensive R Language Analytics Skill for Claude Code</strong>
  <br>
  <em>250+ packages across 15 domains &mdash; data manipulation, visualization, machine learning, and more</em>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/LeoLin990405/r-analytics-skill?style=flat-square" alt="License"></a>
  <a href="https://github.com/LeoLin990405/r-analytics-skill/stargazers"><img src="https://img.shields.io/github/stars/LeoLin990405/r-analytics-skill?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/LeoLin990405/r-analytics-skill/issues"><img src="https://img.shields.io/github/issues/LeoLin990405/r-analytics-skill?style=flat-square" alt="Issues"></a>
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-8A2BE2?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R Language">
</p>

<p align="center">
  <a href="#-features">Features</a> &bull;
  <a href="#-quick-start">Quick Start</a> &bull;
  <a href="#-sub-skills-overview">Sub-Skills</a> &bull;
  <a href="#-project-structure">Structure</a> &bull;
  <a href="CONTRIBUTING.md">Contributing</a>
</p>

**English** | [中文](README_CN.md)

---

## Features

| Metric | Value | Details |
|--------|------:|:--------|
| **Domains** | 15 | Data, Viz, ML, Web, Spatial, Network, NLP, Stats, Bio, Dev, Parallel, Syntax, Language API, Logging, Learning |
| **Categories** | 70+ | Specific sub-domains within each area |
| **Packages** | 250+ | Individual R package skill files |
| **SKILL.md files** | 357 | Total skill definitions across the tree |
| **References** | 18 | Curated guides covering R4DS, Advanced R, Graphics Cookbook, Tidyverse, Bioconductor |

### Highlights

| Area | Key Packages |
|------|--------------|
| Data Manipulation | dplyr, data.table, tidyr, purrr, lubridate, arrow |
| Visualization | ggplot2, plotly, leaflet, highcharter, echarts4r, gganimate |
| Machine Learning | tidymodels, caret, mlr3, xgboost, lightgbm, keras, torch |
| Web & Reports | Shiny, plumber, rmarkdown, quarto, httr2 |
| Spatial Analysis | sf, terra, tmap, leaflet, stars |
| Bioinformatics | DESeq2, GenomicRanges, Biostrings, edgeR |

---

## Quick Start

### Installation

```bash
cd ~/.claude/skills
git clone https://github.com/LeoLin990405/r-analytics-skill.git r-analytics
```

### Verify

```bash
ls ~/.claude/skills/r-analytics/SKILL.md
```

### Usage

Once installed, Claude Code automatically picks up the skill. Just ask naturally:

```text
"How do I use dplyr to filter and summarize data?"
"Create a ggplot2 scatter plot with regression line"
"Show me how to use tidymodels for classification"
"Analyze this CSV file with R"
```

### Requirements

- **R** 4.0+
- **Claude Code** CLI

---

## Sub-Skills Overview

| Sub-Skill | Directory | Description |
|-----------|-----------|-------------|
| **R Data** | `sub-skills/r-data/` | Data manipulation, formats, databases (dplyr, data.table, DBI, arrow) |
| **R Viz** | `sub-skills/r-viz/` | Visualization (ggplot2, plotly, leaflet, HTML widgets) |
| **R ML** | `sub-skills/r-ml/` | Machine learning (tidymodels, xgboost, caret, deep learning) |
| **R Web** | `sub-skills/r-web/` | Web technologies & reproducible research (Shiny, rmarkdown) |
| **R Stats** | `sub-skills/r-stats/` | Bayesian analysis, optimization, finance (Stan, quantmod) |
| **R NLP** | `sub-skills/r-nlp/` | Natural language processing (tidytext, quanteda, tm) |
| **R Bio** | `sub-skills/r-bio/` | Bioinformatics (Bioconductor, DESeq2, GenomicRanges) |
| **R Network** | `sub-skills/r-network/` | Network analysis (igraph, tidygraph, visNetwork) |
| **R Spatial** | `sub-skills/r-spatial/` | Spatial analysis (sf, terra, leaflet, tmap) |
| **R Dev** | `sub-skills/r-dev/` | R development (devtools, testthat, roxygen2, Rcpp) |
| **R Parallel** | `sub-skills/r-parallel/` | Parallel computing & performance (future, Rcpp, Spark) |
| **R Syntax** | `sub-skills/r-syntax/` | Pipe operators & syntax extensions |
| **R Language API** | `sub-skills/r-language-api/` | Python, JavaScript, Java, C++ interfaces |
| **R Logging** | `sub-skills/r-logging/` | Application logging frameworks |
| **R Learning** | `sub-skills/r-learning/` | Interactive learning tools |
| **R Resources** | `sub-skills/r-resources/` | Learning resources (books, courses, cheat sheets) |

---

## Project Structure

```
r-analytics-skill/
├── SKILL.md                  # Main skill entry point
├── README.md                 # This file
├── README_CN.md              # Chinese documentation
├── LICENSE                   # MIT License
├── CONTRIBUTING.md           # Contribution guidelines
├── CHANGELOG.md              # Release history
├── .github/
│   ├── workflows/
│   │   └── claude-review.yml # CI workflow
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml    # Bug report template
│   │   ├── feature_request.yml # Feature request template
│   │   └── config.yml        # Issue template config
│   └── PULL_REQUEST_TEMPLATE.md
├── references/               # 18 curated reference guides
│   ├── r4ds-*.md             # R for Data Science (2e)
│   ├── advr-*.md             # Advanced R (2e)
│   ├── graphics-cookbook.md   # R Graphics Cookbook
│   ├── tidyverse-ecosystem.md
│   ├── bioconductor.md
│   ├── awesome-packages.md
│   └── ...
├── scripts/
│   ├── update_packages.R     # Package updater
│   └── example.py
├── assets/
└── sub-skills/               # 15 domain-specific skill trees
    ├── r-data/               # Data manipulation
    ├── r-viz/                # Visualization
    ├── r-ml/                 # Machine learning
    ├── r-web/                # Web & reports
    ├── r-spatial/            # Spatial analysis
    ├── r-network/            # Network analysis
    ├── r-nlp/                # NLP & text mining
    ├── r-stats/              # Statistics & finance
    ├── r-bio/                # Bioinformatics
    ├── r-dev/                # R development
    ├── r-parallel/           # Parallel computing
    ├── r-syntax/             # Syntax extensions
    ├── r-language-api/       # Language interfaces
    ├── r-logging/            # Logging frameworks
    ├── r-learning/           # Learning tools
    └── r-resources/          # Learning resources
```

---

## References

The `references/` directory contains curated guides:

| Guide | Topics |
|-------|--------|
| **R for Data Science (2e)** | ggplot2, dplyr, tidyr, readr, purrr, functions |
| **Advanced R (2e)** | Foundations, FP, OOP, metaprogramming, performance |
| **R Graphics Cookbook** | Bar, line, scatter, distributions, annotations, colors |
| **Tidyverse Ecosystem** | Core packages, import tools, modeling patterns |
| **Bioconductor** | Installation, GenomicRanges, RNA-seq, annotation |
| **Awesome Packages** | Curated list by domain (ML, viz, web, finance, etc.) |

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:

- Adding new package skills
- Improving existing skill files
- Adding references and examples
- Reporting bugs and requesting features

---

## Contributors

- **Leo** ([@LeoLin990405](https://github.com/LeoLin990405)) - Project Lead & Curation
- **Claude** (Anthropic Claude) - Content Generation & Organization

## Acknowledgements

- **[Hadley Wickham](https://hadley.nz/)** - For tidyverse, ggplot2
- **[RStudio/Posit](https://posit.co/)** - For the R ecosystem
- **[CRAN](https://cran.r-project.org/)** - For hosting R packages
- **[Bioconductor](https://bioconductor.org/)** - For bioinformatics packages

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
