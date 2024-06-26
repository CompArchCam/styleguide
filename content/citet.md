+++
title = "citation as nouns"
+++

Citations are not nouns. For example, this is wrong:

- *We build on the work of [32].*

The right way is to either name the system or the authors:

- *We build on Terra [32].*
- *We build on the work of Cookie Monster et al. [32].*

The [natbib][] package for LaTeX defines the `\citet` macro, which automatically
adds the names of the authors and the citation.
It provides several other [useful macros][natbib-macros] for citations.

When writing in LaTeX, put a tilde (~) before the citation macro to avoid a line break before it.
For example:

- `We all love LaTeX~\cite{Lamport}.`

[natbib]: https://ctan.org/pkg/natbib?lang=en
[natbib-macros]: http://merkel.texture.rocks/Latex/natbib.php
