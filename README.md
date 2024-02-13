## A Notebook with my Thesis Results

This directory contains the source code for a cluster analysis that I performed on my thesis data. The results are consolidated in a notebook, which I then publish to html on the `gh-pages` branch of this repository

-  `index.qmd`
This is the quarto notebook that I am sharing with my thesis committee to get their feedback on the suitability of the different clustering methods.
-  `_quarto.yml`
This tells quarto to render my notebook locally in the `docs/` directory.
-  `.gitignore`
This tells git to ignore the local `docs` directory where I render my notebook. To actually publish the notebook I use `quarto publish gh-pages`
