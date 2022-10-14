

## Steps to get cpp only document

Step 1. After cloning do the following
```
grep '\ffreeexample' --include=*.tex -rl . | xargs sed -i 's/\\ffreeexample/%\\ffreeexample/g'
grep '\fexample' --include=*.tex -rl . | xargs sed -i 's/\\fexample/%\\fexample/g'
grep '\fnexample' --include=*.tex -rl . | xargs sed -i 's/\\fnexample/%\\fnexample/g'
```
Step2. Run `make`.

# OpenMP Examples Document (CPP programs only)

This is the OpenMP Examples document in LaTeX format.

Please see [Contributions.md](Contributions.md) on how to make contributions to adding new examples.

For a brief revision history, please see [Changes.log](Changes.log).

For copyright information, please see [omp_copyright.txt](omp_copyright.txt).

