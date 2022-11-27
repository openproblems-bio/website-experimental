## OpenProblems NBT2022 reproducibility

An experimental repository for producing the results from the NBT 2022 paper.


## Installation

* Install [quarto](https://quarto.org), R and Python.

* Run `Rscript -e 'install.packages("renv")` if you don't have `{renv}` installed.

* Run `Rscript -e 'renv::restore()'` to install R and Python packages recorded in the renv lockfile (`renv.lock`) and Python requirements (`requirements.txt`).
  This might take a while.

* Download a `results.zip` from the OpenProblems GitHub Action named [Process Nextflow results](https://github.com/openproblems-bio/openproblems/actions/workflows/process_results.yml) and extract in the `results/` folder.

## Preview

Run `quarto preview` to render a preview version of the site.

## Build

Run `quarto build` to render the site.