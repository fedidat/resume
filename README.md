This is the tool that generates my resume in English, French and Hebrew,
from Markdown to HTML, ODT, DOC and PDF.

Many thanks for the wonderful idea and execution to [Jack Senechal](https://github.com/jacksenechal/resume)!

Read the blog posts about it ([part 1](https://fedidat.com/150-resume/), [part 2](https://fedidat.com/210-resume-pt-2/)).

Dependencies: LibreOffice 6+, pandoc 2.4.1+ as `/usr/bin/pandoc` (solves interference with `conda`), fonts-cmu.

Ignore the `unknown IO error` needlessly printed to terminal [by a version check since OO 6](https://bugs.documentfoundation.org/show_bug.cgi?id=108402).