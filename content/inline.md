+++
title = "inline maths & code"
+++
You often want to put maths, code or other notation in the flow of prose.
Do it like this:

    Introductory sentence, ending with a colon:
    %
    \[ e = m \times c^2 \]
    %
    More explanation here.

The text leading up to the notation should give enough context so that the reader knows why they are about to see an equation.
It should call out the key insight they should look for while trying to understand the maths or listing.
The text afterwards should provide justification and explain details that make sense after seeing the notation.

Above and below the maths or listing, use an empty TeX comment line (`%`) to avoid starting a new paragraph whilst still making the TeX look readable.

For maths, be sure to use display-mode maths macros like `\[ x \]` or `align*`.
Use `align*` (instead of several `\[ \]` equations in a row) when you have multiple lines:

    \begin{align*}
    S &= \frac{T_s}{T_p} \\
      &= \frac{1}{(1 - p) + \frac{p}{s}}
    \end{align*}
