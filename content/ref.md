+++
title = "references"
+++
To reference a section, use `section~\ref{...}`. Only capitalise *section* if it starts a sentence and use a tilde to make a nonbreaking space. (And the same for tables and figures.) Always use *section*, even when it’s a subsection or subsubsection.

When explaining figures or tables that show results, refer to them early in the paragraph, usually in the first sentence, and then explain the contents in more detail. For example:

> Figure 9 shows the execution time for each benchmark relative to an unmodified execution. The geometric mean slowdown is 8%. The worst slowdown is streamcluster, which is 31% slower with debugging enabled.

It’s usually best to put the figure or table reference right at the beginning of the sentence and to follow it with an active verb.
For example, prefer *Figure N shows X* to *X can be found in figure N* or *As shown in figure N, X*.

In LaTeX, consider using the `cleveref` package to help with this formatting and to deal with lists of multiple labels automatically.
