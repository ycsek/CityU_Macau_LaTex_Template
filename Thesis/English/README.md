# City University of Macau FDS BCS Bachelor's Thesis Template

This project is an LaTeX adaptation of the official Faculty of Data Science undergraduate graduation thesis format at City University of Macau.

The template is based on the Faculty of Data Science official undergraduate thesis template documents and writing guidelines. It follows the required thesis structure, including the individual-format cover, approval page, declaration insertion, front matter, chapter organization, references, author resume, and appendix.

## Official guideline links

- Official Faculty guideline page: https://fds.cityu.edu.mo/upcoming_events/552

The English Faculty page lists the undergraduate graduation project thesis requirements and related annexes, including the FDS undergraduate graduation project thesis report template and writing guideline.

## Local reference documents

The local workspace includes the official Word/PDF reference documents used when preparing this LaTeX adaptation:

- `FDS本科生畢業設計論文報告模板.doc`
- `DECLARATION.pdf`

If the Overleaf Gallery submission should not include the original official Word/PDF files, keep this README and remove those source reference documents from the uploaded project archive.

## Important note

This project is not maintained by City University of Macau. It is an LaTeX implementation based on the official Faculty of Data Science guidelines and template documents.

## Compilation

Use pdfLaTeX and BibTeX:

```bash
pdflatex main
bibtex main
pdflatex main
pdflatex main
```
