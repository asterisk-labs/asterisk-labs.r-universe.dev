# Asterisk Labs R Universe

R packages developed at [Asterisk Labs](https://asterisk.coop), the
UK's first worker-owned cooperative research laboratory focused on
deep learning, Earth observation, and climate science.

Browse the universe: <https://asterisk-labs.r-universe.dev>

## Install any package

```r
install.packages("taco", repos = "https://asterisk-labs.r-universe.dev")
```

## Packages

| Package | Description |
|---------|-------------|
| [cozip](https://asterisk-labs.r-universe.dev/cozip) | Cloud-Optimized ZIP — open a ZIP like a table |
| [taco](https://asterisk-labs.r-universe.dev/taco) | Read TACO datasets in R |

## How this works

This repository is the manifest for the Asterisk Labs r-universe. The
`packages.json` file lists every package, its source repository, and
its location within that repository. [r-universe](https://r-universe.dev)
polls these repos, builds the packages on Linux, macOS, and Windows,
and serves them as a CRAN-like repository.

To add a package, edit `packages.json` and open a pull request.
