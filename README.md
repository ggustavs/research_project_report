## Research Project Report

This directory stores the LaTeX sources for *“Updating the Vehicle-lang Python bindings to support training with constraints.”* The write-up covers why the bindings were updated, how the new Python abstractions line up with Vehicle, and what tests validate why the update achieves what I set out to do.

### Contents

- `main.tex` pulls the document together and defines the listing/glossary helpers.
- `1introduction.tex` … `5conclusions.tex` are the core chapters (motivation, background, approach, evaluation, conclusions).
- `appA.tex`, `appB.tex`, `appC.tex` hold overflow content—proofs, data tables, larger figures.
- `thesis.bib` stores the citation entries.
- `src/` keeps shared figures (`ITUlogo.jpg`, `samplefig.pdf`, etc.).
- `main.pdf` is the last compiled draft that went to review.

### Purpose

This repo exists purely as a record of the Vehicle Python binding refresh. It mirrors the submission sent to ITU, so it is easy to trace what changed and reuse sections later. It is not meant as a contributor guide.
