# Reviewing Python-Based Research (Without Being a Coder)

Code review is a vital part of research quality assurance, and it need not be intimidating—whether you are a supervisor, a PhD student, or a peer reviewer. Even if you are not a programmer yourself, you can still contribute meaningfully to the review of Python-based work by focusing on structure, clarity, documentation, and reproducibility. Reviewing code is less about understanding every technical detail and more about asking the right questions and promoting good scientific practice.

## Understanding the Essentials

When approaching a Python-based project, start by focusing on accessibility and transparency rather than the specifics of the code itself. Ask yourself:

- **Is there a clear README or project description?**  
  Every project should begin with a simple, human-readable explanation of its purpose. What research question or hypothesis is being addressed? What is the role of the code within the broader project?

- **Are the inputs and outputs well explained?**  
  You should not need to dive into the code to understand what data is required, how it should be formatted, and what outputs are produced. Look for clear documentation or examples.

- **Is the data properly documented and structured?**  
  Data should be accompanied by descriptions of its origin, any cleaning steps, and its format. Good practice includes the use of consistent naming conventions and logical folder structures.

- **Is the work reproducible and extendable?**  
  Consider whether a future researcher—perhaps even one unfamiliar with the project—could rerun the scripts, reproduce the results, and build upon the work. Version-controlled codebases (for example, those using Git) and clear dependency management (such as a `requirements.txt` file or `environment.yml`) are good signs.

## Practical Suggestions for Non-Coders

If you are not comfortable reading Python code line by line, you can still review a project effectively by encouraging the following practices:

- **Request a walkthrough.**  
  Ask the researcher to walk you through the project live. Have them explain each step of the process verbally, from input data to final output. This exercise often reveals hidden assumptions and gaps in clarity.

- **Ask for a visual workflow.**  
  A simple diagram showing the flow from inputs through processing steps to outputs can help you—and the researcher—gain a bird’s-eye view of the project. Tools like miro, plantuml.io, draw.io, Lucidchart, or even hand-drawn sketches can be sufficient.

- **Examine the project structure.**  
  Well-organised folders and files signal professional habits. Look for folders such as `data`, `scripts`, `notebooks`, and `results`, and check that file names are descriptive.

- **Look for collaboration practices.**  
  Check whether the project uses Git or a similar version control system. A meaningful commit history, descriptive commit messages, and open issues or pull requests suggest that the project is being developed thoughtfully and collaboratively. Internal documentation, such as docstrings (brief comments inside the code explaining functions), is also an excellent sign.

- **Evaluate user-friendliness.**  
  Ask yourself: If I were handed this project without guidance, how easily could I get it running? A "Getting Started" section, a list of requirements, and clear instructions for running key scripts are essential.

## Guidance for Coders Reviewing Coders

For those with some coding background, code review should also focus on technical robustness, maintainability, and scientific soundness. Consider:

- **Is the code modular and readable?**  
  Code should be divided into functions or classes, each performing a clear task. Variable and function names should be descriptive and consistent.

- **Is there error handling?**  
  Good code anticipates possible problems (such as missing files or bad data formats) and provides helpful error messages.

- **Are there tests?**  
  Unit tests or integration tests help ensure that parts of the codebase behave as expected, even as the project evolves.

- **Is the code efficient and appropriate for the task?**  
  Python has many libraries designed for efficient data handling (such as `numpy` or `pandas`), and these should be used where appropriate. However, over-engineering or premature optimisation should be avoided in research code.

- **Is the scientific method preserved?**  
  Ensure that the code correctly implements the intended analysis or model. Pay attention to assumptions, parameter choices, and any stochastic elements. Reproducibility must remain a priority.

## Creating a Supportive Review Environment

Whether you are reviewing as a supervisor, a collaborator, or a peer, remember that code review should be a constructive, collegial process. The aim is not to "catch mistakes" but to strengthen the work. Approach the review with curiosity and humility: no code is perfect, and every review is an opportunity to learn together.

Encourage a mindset of continuous improvement, highlight strengths as well as areas for development, and frame feedback around the goal of making the research more reliable, understandable, and reusable.

## Further Reading

For those interested in diving deeper into best practices for code review, Google's Engineering Practices documentation offers an excellent, detailed guide: [Google Engineering Practices – Code Review](https://google.github.io/eng-practices/review/). Although written with software engineering teams in mind, many of its principles—such as clarity, correctness, design, and constructive communication—are equally applicable to academic research settings.

---