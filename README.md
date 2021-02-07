# md2pdf-rapport

This a template for a pretty conversion of a markdown written documentation to pdf on `MacOS`.

# Dependencies

    brew install mactex pandoc

# build

    pandoc rapport.md -s \
    --pdf-engine=xelatex \
    -V mainfont="Arial" \
    -V monofont="Menlo" \
    -V urlcolor=cyan \
    -V papersize:a4paper \
    -V geometry:vmargin=2cm \
    -V geometry:hmargin=3cm \
    -V block-headings \
    -V subparagraph \
    --toc -N \
    -o rapport.pdf;

    open rapport.pdf

# Note

all fonts should be installed by default on a MacOS system.

If you want to use a custom font. Make sure that it's installed on the user's Library.
