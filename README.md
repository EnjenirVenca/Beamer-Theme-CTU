# Beamer-Theme-CTU

The project is inspired by [Beamer-Theme-Execushares-Remastered](https://github.com/ChosenOne2241/Beamer-Theme-Execushares-Remastered); compared to the remastered version, it modifies the fonts and colors to align with the CTU design manual, ensuring consistency and cohesion with the university's visual identity.

* It uses the CTU defined colors for blocks and anything else.
* Unfortunately it does not use the Technika font, rather the Source Sans Pro due to better compatability with Latex
* Fixes the hyperref error warning.  
* Added code block example at the end.

Compilation order: run `pdflatex` on `Main.tex` first, then invoke `biber` (instead of `bibtex`), and finally apply `pdflatex` **two more times**.

* TODO list:
    1. Add the white logo to all the slides.