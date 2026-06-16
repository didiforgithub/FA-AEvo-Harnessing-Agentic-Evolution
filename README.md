# FA-AEvo: Harnessing Agentic Evolution

This repository contains the Foundation Agents edition of the paper source for
**Harnessing Agentic Evolution**.

The layout uses the Foundation Agents LaTeX template and follows the design
language of Google's open-access research paper templates while keeping the
visible paper surface under Foundation Agents branding.

## Build

```bash
latexmk -pdf main.tex
```

The generated paper is `main.pdf`.

## Files

- `main.tex`: Foundation Agents formatted paper entry point.
- `foundationagents.cls`: paper class used by this edition.
- `files/`: section sources.
- `images/`: figure assets.
- `assets/`: Foundation Agents header assets.
- `cited.bib`: bibliography.

## Notes

The class disables paragraph indentation and uses paragraph spacing instead,
matching the current Foundation Agents paper template.
