# When Blocks Build Societies: Multi-Agent Systems in Minecraft

This repository contains all materials for the seminar paper "When Blocks Build Societies: Multi-Agent Systems in Minecraft" by Jan-Philipp Kiel (University of Cologne, 2025).

## Use of Generative AI
This paper was co-created using generative AI throughout the entire research, writing, and revision process. All major steps—from literature review to drafting, analysis, and editing—involved the use of AI models and tools, with human oversight and final editorial control.

## Documenting the Co-Creation Process
During the work on this paper, it became clear that maintaining a detailed research log in the appendix would be too extensive and potentially cluttered for readers. Instead, to avoid redundancy and ensure transparency, the iterative co-creation process with generative AI was documented using git: each prompt and its resulting changes were committed individually where possible. This allows readers to explore the full history of the paper's development, compare versions, and understand how each prompt shaped the artifact. Earlier commits may reflect larger changes spanning multiple prompt iterations, as the approach evolved through experimentation. The complete commit history is available in the public repository. For further details, see the methodology section of the paper.

### Commit Example
Each commit documents the prompt and the resulting change to the artifact. The following template was used to structure commit messages:

```md
<Short, clear summary of all major changes>
[Tool: <Tool Name | Configuration>]

Prompt:

1. [Model: <Model Name | Version>]
    """
    <Prompt #1>
    """
    Result: <Description of the change to the artifact>
2. [Model: <Model Name | Version>]
    """
    <Prompt #2>
    """
    Result: <Description of the change to the artifact>
...
<Comments or general notes if helpful>
```

## Repository Structure
```
├── paper.tex                   # LaTeX source for the paper
├── literature.bib              # Bibliography file
├── paper.pdf                   # Current compiled paper
├── paper-draft.pdf             # Draft version of the paper
├── paper-draft-peer-review.pdf # Peer review of the draft paper
├── paper-outline.md            # Markdown outline of the paper
├── slides-final.pdf            # Final presentation slides
├── slides-midterm.pdf          # Midterm presentation slides
├── latex.code-workspace        # VS Code workspace settings
├── README.md                   # This file
└── appendix/                   # Supplementary materials and figures
```

## Compilation
1. Ensure you have a LaTeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/) for macOS/Linux or [MiKTeX](https://miktex.org/) for Windows) and `biber` installed.
2. In your terminal, run:
   ```zsh
   pdflatex paper.tex
   biber paper
   pdflatex paper.tex
   pdflatex paper.tex
   ```
3. Or use [Visual Studio Code](https://code.visualstudio.com/) and the [LaTeX Workshop extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) to handle most compilation steps for you. 
4. The output will be many auxiliary files and a new `paper.pdf`.

## License
This repository is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/). See the [LICENSE](LICENSE) file for more information.

## Citation
If you use or reference this work, please cite as:

> Kiel, J.-P. (2025). When Blocks Build Societies: Multi-Agent Systems in Minecraft (Unpublished seminar paper). University of Cologne, Advanced Seminar: Information Systems and Digital Technology.
