# CTiML_Proposal

Project proposal for Current Topics in Machine Learning: *Not All Perturbations Decontaminate: Classifying Effective vs. Leaky Problem Rewrites in Dynamic Code Benchmarks*.

## Files

| file | purpose |
|---|---|
| `project_proposal.tex` | proposal source (edit this) |
| `egbib.bib` | references |
| `iccv.sty` | course template style |
| `fig_peft_vs_full.pdf` | Figure 1 (LoRA vs. full fine-tuning) |
| `project_proposal.pdf` | compiled proposal |

## Build

```bash
latexmk -pdf project_proposal.tex
```

Or, without latexmk:

```bash
pdflatex project_proposal.tex
bibtex project_proposal
pdflatex project_proposal.tex
pdflatex project_proposal.tex
```

`latexmk -c` removes build files. On Overleaf, upload all files and use the pdfLaTeX compiler.

## Constraints

- Main text must fit in **2 pages**, excluding references.
- Cite roughly 3–5 closely related papers.

## Contributing

Create a branch, edit `project_proposal.tex` (and `egbib.bib` for new references), check that the PDF still builds within the page limit, then open a pull request.
