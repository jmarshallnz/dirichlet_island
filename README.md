# Extending statistical models for source attribution of zoonotic diseases

## A study of campylobacteriosis

This repository contains the necessary material to reproduce the paper
*Extending statistical models for source attribution of zoonotic diseases: A study of campylobacteriosis*

## Dependencies

This paper depends on code and data released as part of the [`islandR` package](https://github.com/jmarshallnz/islandR)

Some of the tables additionally require population information available from the [`meshblocknz` package](https://github.com/jmarshallnz/meshblocknz).

Both may be installed using `devtools`:

```
devtools::install_github('jmarshallnz/islandR')
devtools::install_github('jmarshallnz/meshblocknz')
```

In addition, some standard packages from the [tidyverse](http://tidyverse.org) are required, such as `dplyr`, `tidyr`, `ggplot2`
and so on.

## Data

The data are available in the `islandR` package as `manawatu`:

```
library(islandR)
head(manawatu
```

## Code

Code for all figures are available in the `fig_foo.R` files. Code for the tables and other
data used in the text is in `tables.R`. Note that the table for DIC first requires that
`fig_attribution.R` has run.

## Questions/comments

Questions about the R package `islandR` should be directed to the [issues page of the `islandR` package](https://github.com/jmarshallnz/islandR/issues)

Questions about the paper may be directed to the [issues page here](../../issues).
