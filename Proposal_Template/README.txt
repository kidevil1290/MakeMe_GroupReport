CIS 3296 — Individual Project Proposal Template
===============================================

You can write the proposal in Overleaf (easiest, nothing to install) or in any LaTeX editor on your own computer, for example TeXstudio, TeXworks, or VS Code with the LaTeX Workshop extension.

OVERLEAF
--------
1. Download this ZIP from Canvas.
2. Open Overleaf.
3. Choose New Project > Upload Project.
4. Upload the ZIP without extracting it.
5. Open main.tex.
6. Edit the three student-information lines near the top
   (project title, your name, proposal type).
7. Replace the placeholder proposal text.
8. Replace the two example references in references.bib with real sources.
9. Add your diagrams and images to the figures/ folder.
10. Compile the project and check that the PDF, figures, citations,
    and References section appear correctly.

OTHER LATEX EDITORS (on your computer)
--------------------------------------
1. Download and unzip the ZIP. Keep all files and the figures/ folder together.
2. Open main.tex in your editor.
3. Install a full LaTeX distribution (TeX Live or MiKTeX). It must include Biber, which the bibliography needs.
4. Compile with the recommended command:
       latexmk -pdf main.tex

   Alternative:
       pdflatex main.tex
       biber main
       pdflatex main.tex
       pdflatex main.tex

   Most editors have a build button that does this. If your citations
   show as [?] or the References section is empty, the editor did not run
   Biber. Use the command above instead.

PACKAGE CONTENTS
----------------
main.tex                Main proposal source
references.bib          Example bibliography entries + source templates
CITATION_EXAMPLE.txt    Step-by-step citation example
figures/                UML diagrams and supporting figures
figures/temple-logo.png Temple University Japan logo used on title page
main.pdf                Compiled template preview

EXPECTED FIGURE NAMES
---------------------
figures/use-case-diagram.pdf
figures/class-diagram.pdf
figures/feasibility-evidence.png

The filenames can be changed by editing the corresponding
\includegraphics command in main.tex.

IMPORTANT
---------
- Delete the demonstration citation example from main.tex before submission.
- Replace the example entries in references.bib with real sources.
- If you still see a gray "Add figures/..." box in the PDF, the figure
  file name or folder is incorrect.
- Overleaf and local editors produce the same final document.
- Submit the completed ZIP according to the Canvas assignment instructions.
- BACKUP: Overleaf saves automatically, but you are responsible for your
  own copy. Download the source ZIP (Menu > Download > Source) after each
  work session and keep it on your computer or cloud storage.
  Do not delete your Overleaf project until the proposal is submitted.