# Guide to writing clean code

Below are my notes from [Gregor Sturm's](https://github.com/grst) article titled [Hallmarks of Good Scientific Software](https://grst.github.io/bioinformatics/2020/07/16/hallmarks-scientific-software.html)

### Write easy-to-read code:
1. Format code consistently
2. Use simple variable names
3. Keep it super simple

Here is a [style guide for R](http://stat405.had.co.nz/r-style.html) and [clean-code-python](https://github.com/zedr/clean-code-python#introduction) project.

### Hallmarks of Good Scientific Software
1. Use version control (i.e. [git](http://git-scm.com/) and [GitHub](https://github.com/) or [GitLab](https://gitlab.com/))
2. Use automated testing and continuous integration (i.e. [GitHub Actions](https://docs.github.com/en/actions), [pytest](https://docs.pytest.org/en/latest/), and [testthat](https://testthat.r-lib.org/))
3. Containerize dependencies (i.e. [Singularity](https://sylabs.io/docs/), [Docker](https://www.docker.com/), and [Bioconda](https://bioconda.github.io/))
4. Write extensive, high-quality documentation (i.e. [sphinx](https://www.sphinx-doc.org/en/master/) and/or [pkgdown](https://pkgdown.r-lib.org/))
5. Write self-reporting data-analyses (i.e. Rmarkdown and/or Jupyter Notebooks)
6. Use a workflow manager (i.e. [Nextflow](https://www.nextflow.io/) and/or [Snakemake](https://snakemake.readthedocs.io/en/stable/))
