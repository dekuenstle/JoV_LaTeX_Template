# Journal of Vision article: LaTeX template

A LaTeX template to generate PDFs that look similar to [Journal of Vision](https://jov.arvojournals.org/) articles (two-column design). 

This unofficial template is not affiliated with the ARVO Foundation or the Journal of Vision.
However, it can generate an article draft and submission that resembles the final paper's appearance. 

## Line spacing and numbers

Increased line spacing and line numbers can be helpful in writing and correcting article drafts.
This is why these are activated by default but can be deactivated to resemble the JoV article design more closely.

To deactivate line numbers and spacing, comment out these lines in `jov.cls`:
```tex
\RequirePackage[modulo]{lineno}
\linenumbers
\linespread{1.5}
```

## Supplementary material

In addition to the two-column article template, there is a one-column template to create supplementary materials in a consistent layout. 

The supplementary file is included at the end of the main file; compile both with the main file. 

## License

David-Elias Künstle created this template by adapting the [JoV manuscript template by Tobias Elze](http://www.tobias-elze.de/latex/) (one column design of JoV in 2010) to
resemble the appearance of a two-column JoV article in 2024.

This version is free to use, share, and adapt under the [MIT license](https://opensource.org/license/MIT).
