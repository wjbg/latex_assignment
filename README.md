# LaTeX Exam Template

[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A simple LaTeX template for assignments.

The template features:
1. A small header with:
   * The course name and the course code
   * Description of the assignment
   * A due date
   * Contact details
2. A command and an environment for the questions and answers:
   * `\question` for auto-numbered questions; this allows easy
     reshuffling of questions without messing up the numbering order...
   * `\begin{answer} ... \end{answer}` for the answers, which will be
     printed in a yellowish box.

The answers can be shown or hidden using a boolean:

```latex
% ==============================================================================
% Show answers?
%
\showanswerstrue
% \showanswersfalse

```

Check the [pdf](latex_assign_template.pdf) for an impression.

## License

Free as defined in the [GNU General Public
License v3](https://www.gnu.org/licenses/gpl-3.0.en.html).
