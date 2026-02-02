# Copilot Instructions for AI Coding Agents

## Project Overview
This workspace is a collection of Jupyter notebooks and Python scripts focused on teaching and demonstrating data science concepts, especially with NumPy, Pandas, and basic Python graphics (e.g., turtle, matplotlib). The structure is organized by topic, with subfolders for NumPy and Pandas, and notebooks covering specific operations or problems.

## Key Patterns & Conventions
- **Notebook-centric workflow:** Most code is in `.ipynb` files. Each notebook is self-contained, often starting with imports and setup, and demonstrates a single concept or problem.
- **No central build/test system:** There are no Makefiles, requirements.txt, or test scripts. Assume code is run interactively in Jupyter or directly in Python.
- **Visualization focus:** Many notebooks use `turtle`, `matplotlib`, or similar libraries for visual output. When generating new code, prefer inline visualizations and clear, stepwise explanations.
- **Naming conventions:** Notebooks are named descriptively by topic (e.g., `Create NumPy arrays.ipynb`, `Join Pandas DataFrame.ipynb`). New files should follow this pattern for discoverability.
- **Minimal cross-notebook dependencies:** Each notebook should be runnable independently. Avoid introducing shared state or dependencies between notebooks unless explicitly requested.

## Examples & Best Practices
- **NumPy notebooks:** Demonstrate array creation, manipulation, and operations. See `NumPy/Create NumPy arrays.ipynb` and `NumPy/Statistical Operations on NumPy Arrays.ipynb` for style and structure.
- **Pandas notebooks:** Focus on DataFrame creation, joining, and attribute exploration. See `Pandas/Create a Pandas DataFrame.ipynb`.
- **Visualization notebooks:** Use `turtle` or `matplotlib` for animation or drawing. See `Human.ipynb` for animated turtle graphics and `matplotlib` image animation.

## Integration & Dependencies
- **External libraries:** Assume `numpy`, `pandas`, `matplotlib`, and `turtle` are available. If a notebook requires a new library, add an installation cell at the top (e.g., `!pip install package`).
- **No hidden configuration:** There are no hidden config files or environment requirements. All setup should be explicit in each notebook.

## AI Agent Guidance
- When adding new notebooks, use clear, topic-focused names and include a markdown cell at the top describing the purpose.
- When updating or refactoring, preserve the self-contained nature of each notebook.
- Prefer code that is easy to read and suitable for teaching or demonstration.
- Do not introduce project-wide dependencies or complex build systems unless explicitly requested.

## Reference Files
- `NumPy/` and `Pandas/` folders: Topic-specific notebooks
- `Human.ipynb`: Example of advanced visualization and animation

---
For questions about unclear conventions or missing documentation, prompt the user for clarification before making structural changes.
