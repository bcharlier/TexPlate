# Quick Start

## Compilation

Edit and compile `main.tex`:

```bash
pdflatex --shell-escape main.tex
```
## Caveat

Make sure your LaTeX distribution is properly configured to support all dependencies. This document uses [`minted`](https://www.ctan.org/pkg/minted) (which relies on [Pygments](https://pygments.org/)) to render code blocks. You must ensure your LaTeX engine allows external programs.


