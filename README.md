# Tiago Meilan

<p align="left">
  <strong>Physics student (UBA) · Applied AI builder</strong> · AI agents, evaluation & verification · Scientific computing for energy
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/tiago-meilan-6a723a260/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:meilantiago@gmail.com"><img src="https://img.shields.io/badge/Email-meilantiago%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Buenos%20Aires%2C%20Argentina-102C57?style=flat&logo=google-maps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Education-B.Sc.%20Physics%20(UBA)-blue?style=flat" alt="Education" />
</p>

---

### 🔬 About

Advanced Physics student at the University of Buenos Aires (expected 2027), oriented to **probability, statistics and mathematical modeling**.

I build software and AI systems by orchestrating AI agents. The agents write most of the code; I keep the decisions that define the quality of the result: the specification, the architecture and the validation criteria. As a physicist, what I care about is that the result is correct and measurable, not just that it runs.

- **Spec-driven development with AI agents**: a Claude Code harness where every change starts as a spec with numbered acceptance criteria, approval is stored as a hash, acceptance tests are written first, and deterministic CI gates decide when work is done.
- **Reliable AI**: retrieval-augmented systems that cite their sources or refuse to answer, evaluated against a human-curated golden set with statistical comparison of configurations.
- **Hardware & control**: at TECSCI I designed a nanometer-precision linear stage for laser micromachining, including its closed-loop control firmware, and raised the encoder resolution by a factor of 60 by rearranging its magnets.
- **Energy**: Python tooling for drilling mechanics, 1D geomechanics and decline curve analysis in Vaca Muerta.

---

### ⚡ Featured Projects

#### 🤖 Applied AI

| Project | What it does | Stack |
|---|---|---|
| [**offshore-incident-rag**](https://github.com/meilantiago/offshore-incident-rag) | Grounded Q&A over ~1,300 public BSEE offshore incident reports and Safety Alerts: every claim cites document and page, or the system declines to answer. Built spec by spec with an SDD harness (hash-bound human approval, AC → test traceability, ruff, mypy strict, evaluation regression gate). **In progress:** ingestion done, structure-aware chunking under way, hybrid retrieval and LangGraph answering next. | `Python` `PostgreSQL` `pgvector` `LangGraph` `Docker` `Claude Code` |

#### 🛢️ Subsurface Energy (Vaca Muerta & Unconventionals)

| Project | Core Domain & Physics | Stack |
|---|---|---|
| [**vaca-muerta-dca**](https://github.com/meilantiago/vaca-muerta-dca) | Production forecasting on public data: 1.95M records filtered to 58k from 2,359 Vaca Muerta shale wells. Modified Arps, Stretched Exponential, weighted least squares, a Random Forest on the residuals and a well-economics module. Documented limitations. | `Python` `Pandas` `PyArrow` `SciPy` `Scikit-Learn` `Pytest` |
| [**drilling-optimization-engine**](https://github.com/meilantiago/drilling-optimization-engine) | Drilling telemetry analytics: LAS ingestion and mnemonic mapping, Mechanical Specific Energy (Teale / Dupriest), stick-slip diagnostics with FFT and Welch PSD, and founder point detection by segmented regression. 52 tests in CI. | `Python` `Lasio` `SciPy` `NumPy` `Pytest` |
| [**geomech-fracability-engine**](https://github.com/meilantiago/geomech-fracability-engine) | 1D Mechanical Earth Model: Biot poroelasticity, overburden, Eaton pore pressure, in-situ horizontal stresses ($\sigma_{h,min}$, $S_{Hmax}$), Rickman brittleness and stress-shadow aware perforation cluster placement on a synthetic benchmark. 25 tests in CI. | `Python` `Lasio` `NumPy` `Matplotlib` `Pytest` |

#### ⚙️ Embedded Control & Instrumentation

| Project | Description | Stack |
|---|---|---|
| [**uMachining**](https://github.com/meilantiago/uMachining) | Closed-loop motion control firmware for a linear laser micromachining axis on a dual-core RP2040: cascaded PID, trapezoidal motion profiles, least-squares encoder calibration, homing and a G-code parser. | `C/C++` `RP2040` `PlatformIO` `SPI` `PID` |

---

### 🛠️ How I Work & Toolchain

- **AI-assisted engineering**: `Claude Code` (subagents, skills, hooks), spec-driven development, human approval at key decisions
- **Verification & evaluation**: test-first acceptance tests, deterministic CI gates, retrieval evaluation (recall@k, MRR, faithfulness), bootstrap confidence intervals and paired tests
- **Scientific computing & data**: `Python`, `NumPy`, `SciPy`, `Pandas`, `PyArrow`, `Scikit-Learn`, `Jupyter`, non-linear fitting, numerical simulation
- **Infrastructure**: `Git`, `GitHub Actions`, `Docker`, `PostgreSQL` + `pgvector`
- **Embedded**: `C/C++` written with AI agents and validated on hardware, `RP2040`, `SPI`, closed-loop control
- **Domain modeling**: decline curve analysis, drilling mechanics (MSE), 1D geomechanics, metrology & sensor calibration

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=meilantiago&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=meilantiago&layout=compact&theme=tokyonight&hide_border=true" width="45%" />
</p>
