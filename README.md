SNO+ RAT github Workflow Walkthrough
====================================
This document explains what the typical user and developer workflow would look like if SNO+ RAT were hosted on github.

Each page is an Inkscape SVG file and (Cairo) PDF copy.

To assembly, use a PDF manipulation tool such as pdftk:

    pdftk title.pdf intro.pdf cheatsheet.pdf gh_trac_main.pdf workflow0.pdf \
        workflow1.pdf workflow2.pdf workflow3.pdf workflow4.pdf workflow5.pdf \
        workflow6.pdf workflow7.pdf workflow8.pdf repos.pdf cat output \
        github_transition.pdf

