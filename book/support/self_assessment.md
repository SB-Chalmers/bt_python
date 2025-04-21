# 🧩 Supporting Python-Based Research Projects: Roles & Responsibilities

A guide for supervisors, PIs, and managers to effectively support research that includes Python workflows — whether for data, simulations, automation, or reproducibility.

---

## Roles & Responsibilities

**🧑‍🔬 Principal Investigator (PI) – Grant Application Stage**  
*Key Task: Enable scalable, reproducible, and fundable technical workflows*
- **Include a data management plan** with structure, access, long-term storage, and expected formats (e.g., CSV, shapefiles, GeoJSON).
- **Justify need for** research software engineers (RSEs), cloud/HPC resources, and time for code development, documentation, and reproducibility.
- **Include reproducibility or open-source goals** (e.g., JOSS submission) as part of deliverables.
- **Plan team capacity:** who’s analyzing, who’s building, who’s documenting?
- **Make room for infrastructure work** as valid research output (esp. in digital twins, ABMs, simulations).

**👩‍🏫 Supervisor – Early-Stage PhD**  
*Key Task: Set up good habits and scalable workflows from the start*
- **Clarify project ambition:** “One-time analysis” vs. “Reusable research pipeline”.
- **Support Python learning:** recommend domain-specific tutorials, encourage notebooks and early versioning.
- **Define expectations:** naming conventions, folder structures, script modularity, and documentation practices.
- **Co-develop a minimum reproducible repo structure** together.
- **Help distinguish between:** Python syntax issues, domain knowledge gaps, and conceptual research issues.

**🧑‍🎓 Supervisor – Late-Stage PhD**  
*Key Task: Guide toward publishable, shareable, and citable code*
- **Encourage packaging results as:** research code repos, notebooks (Binder/JupyterBook), JOSS or Zenodo deposits.
- **Allocate time for:** refactoring, documenting, and writing reusable tutorials or method sections.
- **Clarify value of code:** is it just a means to an end, or also an output?
- **Review final outputs for reproducibility:** could someone else rerun it?

**🎓 Supervisor – Master’s Thesis**  
*Key Task: Scope realistically and avoid overengineering*
- **Set realistic technical goals:** not everyone needs to build a library.
- **Provide starter templates:** notebooks, folder structure, sample datasets.
- **Emphasize good habits:** clean naming, clear comments, documented steps.
- **Require a README and final deliverable repo** if the thesis involves code.
- **Coach on time budgeting:** data cleaning often takes 50% of the effort.

**🧑‍💼 Division or Project Manager**  
*Key Task: Create the conditions for success across multiple projects*
- **Establish division-wide coding standards or templates.**
- **Provide a central GitHub/GitLab organization.**
- **Offer or arrange:** internal training, access to RSEs, onboarding docs.
- **Encourage code documentation and preservation** as part of knowledge transfer.
- **Incentivize shared infrastructure:** reusable scripts, common environments.

**🧰 Optional Roles**

- **🧑‍🔧 Research Software Engineer (RSE):**  
  *Support:* Code architecture, testing, reproducibility  
  *Task:* Make pipelines maintainable and production-ready

- **📊 Data Steward / Data Manager:**  
  *Support:* Data sourcing, standardization, documentation  
  *Task:* Ensure data is analysis-ready and compliant with policies

- **🧑‍💻 Collaborator / RA:**  
  *Support:* Assist with specific coding tasks, especially in time-limited projects  
  *Task:* Document work, follow team conventions, communicate blockers

---

# Self-Assessment Forms for Supporting Python-Based Research Projects

A guide for supervisors, PIs, and managers to effectively support research that includes Python workflows — whether for data, simulations, automation, or reproducibility.

---

## 🧑‍🔬 1. Principal Investigator (PI) – Grant Application Stage

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Have I included a clear data management plan in the proposal? | ☐ Yes ☐ No ☐ Not sure | Shows forethought about data reuse, structure, access, and privacy. |
| Have I accounted for time and resources for coding, documentation, and testing? | ☐ Yes ☐ No ☐ Not sure | Coding is a research task, not an afterthought — plan for it. |
| Have I justified the need for an RSE, developer, or technical staff? | ☐ Yes ☐ No ☐ Not sure | Strengthens team capacity and increases project robustness. |
| Have I specified expected data formats and sources? | ☐ Yes ☐ No ☐ Not sure | Standardized inputs/outputs reduce confusion later. |
| Have I included open science or reproducibility goals (e.g. JOSS, Zenodo)? | ☐ Yes ☐ No ☐ Not sure | Makes your project more transparent and valuable to the research community. |
| Have I allocated budget for cloud compute or storage needs? | ☐ Yes ☐ No ☐ Not sure | Anticipates computational demands and avoids project delays. |
| Have I defined roles around code (developer, analyst, reviewer)? | ☐ Yes ☐ No ☐ Not sure | Clear roles help avoid burnout and duplication of effort. |
| Do I treat the codebase as a valid research output? | ☐ Yes ☐ No ☐ Not sure | Supports recognition of technical work, especially in infrastructure-heavy projects. |

---

## 👩‍🏫 2. Supervisor – Early PhD Stage

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Have we discussed the intended role of Python in the project? | ☐ Yes ☐ No ☐ Not sure | Clarifies expectations: automation, data analysis, modeling, etc. |
| Have I helped the student choose relevant Python learning resources? | ☐ Yes ☐ No ☐ Not sure | Reduces frustration and accelerates progress. |
| Do they have a basic folder structure or repo template to begin with? | ☐ Yes ☐ No ☐ Not sure | Prevents early chaos in file and script management. |
| Have I introduced simple practices (README, function modularity, comments)? | ☐ Yes ☐ No ☐ Not sure | Good habits pay off as complexity increases. |
| Can I identify whether a blocker is about code, analysis, or concept? | ☐ Yes ☐ No ☐ Not sure | Helps direct the student to the right kind of help. |
| Have I discussed the difference between “just working” and “reproducible”? | ☐ Yes ☐ No ☐ Not sure | Early awareness builds towards publishable, shareable work. |
| Have I encouraged sharing notebooks or walkthroughs with peers? | ☐ Yes ☐ No ☐ Not sure | Builds a feedback culture and helps students improve communication. |

---

## 🧑‍🎓 3. Supervisor – Late PhD Stage

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Has the code been reviewed or refactored for clarity and reuse? | ☐ Yes ☐ No ☐ Not sure | Reduces technical debt and improves reproducibility. |
| Is there a README, docstrings, or user guide for the analysis code? | ☐ Yes ☐ No ☐ Not sure | Enables others to reproduce, extend, or validate the work. |
| Are they planning to submit code or data to a repository (e.g. GitHub, Zenodo)? | ☐ Yes ☐ No ☐ Not sure | Encourages visibility and recognition for technical work. |
| Could the code be part of a JOSS or methods paper submission? | ☐ Yes ☐ No ☐ Not sure | Turns infrastructure into research output. |
| Has time been allocated for wrapping up technical outputs (code/data)? | ☐ Yes ☐ No ☐ Not sure | Code clean-up often gets pushed aside near submission deadlines. |
| Does the final work reflect good research software practices? | ☐ Yes ☐ No ☐ Not sure | Helps graduates enter academia or industry with stronger skills. |

---

## 🎓 4. Supervisor – Master’s Thesis

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Is the Python workload scoped realistically for the student’s timeline? | ☐ Yes ☐ No ☐ Not sure | Prevents overload and focus loss. |
| Have I provided (or approved) a starting code/notebook template? | ☐ Yes ☐ No ☐ Not sure | Saves time and gives structure. |
| Do they understand the importance of data formatting and structure? | ☐ Yes ☐ No ☐ Not sure | Well-structured data = faster progress. |
| Have I encouraged a final, organized repo or folder as part of submission? | ☐ Yes ☐ No ☐ Not sure | Promotes reproducibility and professionalism. |
| Am I reviewing code quality as part of the assessment? | ☐ Yes ☐ No ☐ Not sure | Recognizes technical work, not just results. |
| Have I guided them to document their pipeline clearly (even briefly)? | ☐ Yes ☐ No ☐ Not sure | Helps future users — and their own memory. |

---

## 🧑‍💼 5. Division/Project Manager

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Is there a shared GitHub or GitLab organization for the division? | ☐ Yes ☐ No ☐ Not sure | Centralizes team code and avoids siloing. |
| Are there code templates or folders available for new projects? | ☐ Yes ☐ No ☐ Not sure | Standardization boosts efficiency. |
| Have I supported internal training or intro sessions for Python? | ☐ Yes ☐ No ☐ Not sure | Builds internal capacity over time. |
| Are RSEs or technical roles recognized in planning and budgeting? | ☐ Yes ☐ No ☐ Not sure | Prevents code becoming everyone’s “extra job.” |
| Is there documentation on code/data handover for departing team members? | ☐ Yes ☐ No ☐ Not sure | Reduces knowledge loss and frustration. |
| Have I encouraged publishing open tools, datasets, or pipelines? | ☐ Yes ☐ No ☐ Not sure | Enhances division reputation and outreach. |

---

## 👩‍💻 6. Research Assistant / Collaborator

| Question | Yes / No / Not Sure | Motivation |
|---|---|---|
| Do I understand the project’s expectations around reproducibility? | ☐ Yes ☐ No ☐ Not sure | Sets clear standards for quality and documentation. |
| Am I using version control (e.g. Git) for my code contributions? | ☐ Yes ☐ No ☐ Not sure | Essential for tracking and collaboration. |
| Have I documented scripts or analysis pipelines with comments or markdown? | ☐ Yes ☐ No ☐ Not sure | Makes work understandable to others (and yourself later). |
| Am I asking for help when unsure about data structure or analysis goals? | ☐ Yes ☐ No ☐ Not sure | Prevents misalignment or wasted time. |
| Do I flag unclear or inconsistent data back to the team? | ☐ Yes ☐ No ☐ Not sure | Encourages upstream fixes and team awareness. |

---

*Feel free to adapt these forms for your own use, or request a printable version, editable doc, or self-assessment tool for your team!*
