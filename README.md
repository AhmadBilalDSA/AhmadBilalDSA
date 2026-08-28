<!-- Dynamic Typing Header -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&weight=600&size=28&pause=1000&color=2088FF&center=true&vCenter=true&width=800&lines=Hi+there,+I'm+Ahmad+Bilal+👋;Data+Analyst+|+Systems+Engineer;Predictive+Analytics+|+Business+Intelligence" alt="Typing SVG" />
</h1>

<p align="center">
  <em>A detail-driven Data Strategist and Systems Engineer with a rigorous foundation in corporate finance. I specialize in translating complex operational datasets into actionable intelligence, building high-performance local data engineering utilities, and securing software workflows.</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/AhmadBilalDES" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Kierninja@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AhmadBilalDSA&label=Profile%20Views&color=2088FF&style=flat-square" alt="Profile Views" />
</p>

---

### ⚡ Quick Status
- 🔭 **Currently Building:** High-performance, air-gapped data engineering utilities.
- 🌱 **Currently Exploring:** Advanced DuckDB optimizations and Rust-based data tooling.
- 🤝 **Open to:** Roles in Data Engineering, Analytics Engineering, or Open-Source collaborations.

---

### 📊 GitHub Stats & Activity

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=AhmadBilalDSA&show_icons=true&theme=tokyonight&hide_border=true&title_color=2088FF" alt="GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=AhmadBilalDSA&layout=compact&theme=tokyonight&hide_border=true&title_color=2088FF" alt="Top Languages" />
</p>
---

### 🧰 Tech Stack & Expertise

<p align="center">
  <!-- Languages & Version Control -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,mysql,postgres,git,github,vscode,linux&theme=dark" alt="Skill Icons" />
  </a>
</p>
<p align="center">
  <!-- Analytics, BI, & Frameworks -->
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white" alt="Polars" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
</p>

---

### 🌟 Open Source Impact & Ecosystem Contributions

I actively contribute to the core infrastructure of major Python data ecosystems and machine learning frameworks:

| 🌐 Project | 🎯 Domain | 💡 Highlight & Contribution |
| :--- | :--- | :--- |
| **[`scikit-learn/scikit-learn`](https://github.com/scikit-learn/scikit-learn)** | Machine Learning | Contributed core algorithmic and numerical enhancements to Python's premier ML library **(PR #34800)**. |
| **[`tobymao/sqlglot`](https://github.com/tobymao/sqlglot)** | SQL Transpiler | Enhanced multi-dialect SQL parsing logic, AST validation, and query transformations. |
| **[`ibis-project/ibis`](https://github.com/ibis-project/ibis)** | Portable Dataframes | Resolved complex data manipulation bugs and optimized unified dataframe backend conversions. |
| **[`scitex-ai/scitex-io`](https://github.com/scitex-ai/scitex-io)** | AI Infrastructure | Improved AI-driven analytical data pipelines and core developer tooling **(PR #166)**. |

#### 🔬 Detailed Engineering Deep-Dives

> **🛡️ Adexa | Unit Testing & Security ([PR #10](https://github.com/David-Axel/Adexa/pull/10))**  
> **Context:** The AI engine lacked coverage to verify if its automated repair strategies were successfully mitigating SQL injection vulnerabilities.  
> **What I Built:** Engineered over 300 lines of comprehensive unit tests in `test_repair_strategies.py`. Validated the engine's behavior against standard SQL injection patterns to ensure generated code patches meet strict security standards. *(Stack: Python, Pytest)*

> **⚙️ py-simple-wrap | Core Implementation & Mocking ([PR #199](https://github.com/sara-czasak/py-simple-wrap/pull/199))**  
> **Context:** The repository required tests for an `easy_sql` utility, but the base module itself was missing from the core directory.  
> **What I Built:** Developed the core `easy_sql.py` execution module to handle `sqlite3` connections. Concurrently built the testing suite (`test_easy_sql.py`), utilizing `unittest.mock.patch` and `MagicMock` to isolate the database connection and validate query execution flows without requiring a live local database. *(Stack: Python, SQLite3, Pytest, Unittest.mock)*

---

### 🛠️ Personal Engineering & Local Data Utilities

I design and build high-performance, air-gapped local-first tools for developers and data teams:

* 🛡️ **`repo-doctor`** — Automated codebase diagnostic and health-check runner auditing secrets, licenses, and AI-readiness.
* 🚀 **`duck-diff`** — High-speed data schema and table diffing utility leveraging embedded DuckDB for massive file reconciliation.
* 🧹 **`sqlean-lint`** — Lightweight local-first SQL static analysis and rule validation engine targeting performance traps.
* 📈 **`dbt-optimizer`** — Compilation analyzer and cost auditor toolkit for dbt core models and DAG dependencies.
* ⚡ **`data-engine-benchmarks`** — Benchmarking framework evaluating speed, memory efficiency, and throughput across local vs. distributed engines (DuckDB, Polars, Pandas).
* 🔍 **`github-issue-hunter`** — Automated search engine and dashboard designed to query, tag, and track high-priority GitHub issues across open-source ecosystems.

---

### 👨‍💻 Professional Experience

* 🏫 **Power BI Developer & Instructor | PNY Trainings (NAVTTC)**
  * Engineered and delivered a comprehensive technical curriculum in Power BI, SQL, and Python; established best practices for ETL pipelines and advanced data modeling.
* 🍕 **Junior Data Scientist | Timmy's Pizza**
  * Optimized local delivery routes, staffing schedules, and supply chain visibility using Pandas and interactive Power BI dashboards.
* ⛽ **Procurement Intern | Sui Northern Gas Pipelines Limited (SNGPL)**
  * Automated supplier performance KPI tracking and streamlined digital workflows, cutting document retrieval times by over 50%.

---

### 📜 Education & Certifications
* 🎓 **Bachelor of Science in Accounting and Finance** — Hailey College of Commerce, University of the Punjab
* 🏆 **IBM Data Science Professional Certificate**
* 🏆 **IBM Data Analyst Professional Certificate**
* 🏆 **Google Advanced Data Analytics Certificate**

---

### 🐍 Contribution Activity Matrix
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AhmadBilalDSA/AhmadBilalDSA/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AhmadBilalDSA/AhmadBilalDSA/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/AhmadBilalDSA/AhmadBilalDSA/output/github-contribution-grid-snake.svg">
  </picture>
</p>

<!-- CI/CD Graphic (Markdown visual representation) -->
<p align="center">
  <code>[ Git Push / PR ] ──► [ GitHub Actions ] ──► [ Linting & PyTest Matrix ] ──► [ Deploy / Publish ]</code>
</p>
