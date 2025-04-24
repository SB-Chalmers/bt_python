
# Supporting Python‑Based Research Projects  
This is a work in progress, please come back later!!

*For Principal Investigators, Supervisors & Managers*  

A practical guide to roles, responsibilities, and self‑assessment tools for research projects that leverage Python workflows — from data analysis to reproducible simulations.

---

## Part I: Roles & Responsibilities  
An at‑a‑glance matrix followed by detailed breakdowns for each role.

### Roles at a Glance

| Role                          | Stage                 | Key Task                                   |
|-------------------------------|-----------------------|--------------------------------------------|
| 🧑‍🔬 **Principal Investigator**  | Grant Application     | Build scalable, reproducible workflows     |
| 👩‍🏫 **Supervisor – Early PhD**   | Project Kickoff       | Establish good coding & data habits        |
| 🧑‍🎓 **Supervisor – Late PhD**    | Pre‑Submission        | Polish code for sharing & citation         |
| 🎓 **Supervisor – Master’s**       | Thesis Development    | Scope realistically & deliver a clean repo |
| 🧑‍💼 **Division/Project Manager** | Program Oversight     | Provide standards, training & infrastructure |
| *(Optional)* **RSE, Data Manager, RA** | —               | Specialized technical support              |

---

<details>
<summary>### 🧑‍🔬 Principal Investigator (PI) – Grant Application Stage</summary>

**Key Task:** Enable scalable, reproducible, and fundable Python‑based research workflows.

**Top Responsibilities:**
1. **Draft a Data Management Plan**: detail structure, access, storage, and formats (CSV, GeoJSON, etc.).
2. **Budget for Technical Staff & Compute**: justify RSEs, HPC/cloud resources, and coding time.
3. **Embed Open Science Goals**: plan for JOSS submissions, Zenodo deposits, or equivalent.
4. **Define Team Roles Early**: who codes, documents, reviews, and maintains infrastructure.
5. **Recognize Infrastructure Work**: treat digital twins, simulations, and pipelines as valid research outputs.

</details>

<details>
<summary>### 👩‍🏫 Supervisor – Early‑Stage PhD</summary>

**Key Task:** Establish foundational habits and scalable workflows from project start.

**Top Responsibilities:**
1. **Clarify Project Scope**: one‑off analysis vs. reusable pipeline.
2. **Recommend Python Resources**: domain tutorials, notebook practices, and version control.
3. **Define Coding Standards**: naming conventions, folder structures, modular scripts.
4. **Co‑develop Repo Template**: minimal reproducible structure together.
5. **Distinguish Blockers**: code syntax, domain theory, or conceptual research issues.

</details>

<details>
<summary>### 🧑‍🎓 Supervisor – Late‑Stage PhD</summary>

**Key Task:** Guide towards publishable, shareable, and citable code.

**Top Responsibilities:**
1. **Encourage Packaging Outputs**: JupyterBooks, Binder configs, and code repos.
2. **Allocate Time for Refactoring**: documentation, tutorials, and method write‑ups.
3. **Clarify Code Value**: output vs. means to an end.
4. **Review for Reproducibility**: can others rerun the analysis seamlessly?
5. **Plan Deposits**: GitHub releases, Zenodo DOIs, or JOSS paper submissions.

</details>

<details>
<summary>### 🎓 Supervisor – Master’s Thesis</summary>

**Key Task:** Scope work realistically and prevent over‑engineering.

**Top Responsibilities:**
1. **Set Achievable Goals**: avoid building full libraries unless needed.
2. **Provide Starter Templates**: notebooks, folder structures, and sample data.
3. **Emphasize Good Habits**: clear comments, README, and documented steps.
4. **Require a Final Repo**: well‑organized deliverable with README.
5. **Coach on Time Budgeting**: data cleaning often takes half the effort.

</details>

<details>
<summary>### 🧑‍💼 Division/Project Manager</summary>

**Key Task:** Create the conditions for success across projects.

**Top Responsibilities:**
1. **Establish Division‑wide Standards**: coding templates and style guides.
2. **Provide Central Repositories**: GitHub/GitLab organization.
3. **Offer Training & Onboarding**: internal workshops and documentation.
4. **Encourage Documentation & Handover**: knowledge transfer protocols.
5. **Incentivize Shared Infrastructure**: reusable scripts and environments.

</details>

<details>
<summary>### Optional Roles</summary>

- **🧑‍🔧 Research Software Engineer (RSE):**
  - *Support:* code architecture, testing, reproducibility
  - *Task:* build maintainable, production‑ready pipelines

- **📊 Data Steward / Data Manager:**
  - *Support:* data sourcing, standardization, metadata
  - *Task:* ensure analysis‑ready, compliant datasets

- **🧑‍💻 Research Assistant / Collaborator:**
  - *Support:* coding tasks, documentation, blocker reporting
  - *Task:* follow conventions, assist reproducibility

</details>

---

## Part II: Self‑Assessment Checklists  
_Use the tables to reflect on project readiness. Tick ✔︎ or ✘, and jot brief notes if needed._

### 1. Principal Investigator (PI)

| Question                                                                    | ✔︎ Yes | ✘ No | ❓ Not Sure |
|-----------------------------------------------------------------------------|:-----:|:----:|:-----------:|
| Included a clear Data Management Plan?                                       | ☐     | ☐    | ☐           |
| Budgeted time & resources for coding, documentation, and testing?           | ☐     | ☐    | ☐           |
| Justified the need for RSEs/HPC resources?                                   | ☐     | ☐    | ☐           |
| Specified expected data formats and sources?                                | ☐     | ☐    | ☐           |
| Embedded open‑science or reproducibility deliverables (JOSS, Zenodo)?        | ☐     | ☐    | ☐           |
| Defined roles around code development, review, and maintenance?              | ☐     | ☐    | ☐           |
| Treat codebase as a valid research output?                                   | ☐     | ☐    | ☐           |

### 2. Supervisor – Early PhD

| Question                                                                  | ✔︎ Yes | ✘ No | ❓ Not Sure |
|---------------------------------------------------------------------------|:-----:|:----:|:-----------:|
| Clarified Python’s role (analysis vs. pipeline)?                           | ☐     | ☐    | ☐           |
| Provided domain‑specific Python learning resources?                        | ☐     | ☐    | ☐           |
| Shared a repo/folder template?                                             | ☐     | ☐    | ☐           |
| Introduced basic coding practices (README, modularity, comments)?          | ☐     | ☐    | ☐           |
| Can distinguish blocker types (syntax vs. concept)?                        | ☐     | ☐    | ☐           |
| Discussed reproducibility vs. “just working”?                              | ☐     | ☐    | ☐           |
| Encouraged peer‑sharing of notebooks?                                      | ☐     | ☐    | ☐           |

### 3. Supervisor – Late PhD

| Question                                                                 | ✔︎ Yes | ✘ No | ❓ Not Sure |
|--------------------------------------------------------------------------|:-----:|:----:|:-----------:|
| Code reviewed/refactored for clarity and reuse?                           | ☐     | ☐    | ☐           |
| README, docstrings, or user guide present?                                | ☐     | ☐    | ☐           |
| Planned code/data deposits (GitHub release, Zenodo DOI)?                  | ☐     | ☐    | ☐           |
| Considering a JOSS or methods paper submission?                           | ☐     | ☐    | ☐           |
| Time allocated for final code/data polishing?                             | ☐     | ☐    | ☐           |
| Reflects strong research‑software practices?                              | ☐     | ☐    | ☐           |

### 4. Supervisor – Master’s Thesis

| Question                                                              | ✔︎ Yes | ✘ No | ❓ Not Sure |
|-----------------------------------------------------------------------|:-----:|:----:|:-----------:|
| Scope of Python work matches thesis timeline?                         | ☐     | ☐    | ☐           |
| Starter templates provided?                                           | ☐     | ☐    | ☐           |
| Importance of data structure emphasized?                              | ☐     | ☐    | ☐           |
| Final repo with README required?                                      | ☐     | ☐    | ☐           |
| Code quality reviewed in assessment?                                  | ☐     | ☐    | ☐           |
| Pipeline documentation guided?                                         | ☐     | ☐    | ☐           |

### 5. Division/Project Manager

| Question                                                      | ✔︎ Yes | ✘ No | ❓ Not Sure |
|---------------------------------------------------------------|:-----:|:----:|:-----------:|
| Central GitHub/GitLab org exists?                              | ☐     | ☐    | ☐           |
| Code templates/folders available?                              | ☐     | ☐    | ☐           |
| Internal Python training supported?                            | ☐     | ☐    | ☐           |
| RSEs/technical roles recognized in budgets?                    | ☐     | ☐    | ☐           |
| Documentation for handover of code/data?                       | ☐     | ☐    | ☐           |
| Publishing shared tools/datasets encouraged?                    | ☐     | ☐    | ☐           |

### 6. Research Assistant / Collaborator

| Question                                                        | ✔︎ Yes | ✘ No | ❓ Not Sure |
|-----------------------------------------------------------------|:-----:|:----:|:-----------:|
| Understand project’s reproducibility expectations?              | ☐     | ☐    | ☐           |
| Using version control (Git)?                                     | ☐     | ☐    | ☐           |
| Documenting scripts/pipelines with comments or markdown?        | ☐     | ☐    | ☐           |
| Asking for help on data or analysis clarifications?             | ☐     | ☐    | ☐           |
| Flagging unclear/inconsistent data to the team?                | ☐     | ☐    | ☐           |

---

## Appendix: Templates & Resources

- [PDF Checklist Template](#)
- [Starter Repo Structure (ZIP)](#)
- [Sample README.md](#)
- [JOSS Submission Guidelines](https://joss.theoj.org/)
- [Zenodo Deposits](https://zenodo.org/)

---

*Feel free to adapt, expand, or embed this guide in your project docs!*

