# curl

**This is an experimental fork of [jeroen/curl](https://github.com/jeroen/curl). It is not a CRAN package.**

This fork maintains the original functionality of the `curl` R package while experimenting with updated Windows UCRT binary bundles built against **libcurl 8.23.0 or later**.

The primary motivation for this fork is to provide Windows UCRT builds that support more recent versions of libcurl than those available in the upstream project.

This is an experimental copy and is not intended to replace the upstream package. Use it at your own discretion.

Bindings to [libcurl](https://curl.se/libcurl/) for performing fully
customizable HTTP/FTP/SCP requests where responses can be processed either in
memory, on disk, or streaming via the callback or connection interfaces. Some 
knowledge of 'libcurl' is recommended; for a more-user-friendly web client see
the 'httr2' package which builds on this package with http specific tools and logic

## Installation

This package is not available from CRAN. Install the experimental fork directly from GitHub using `remotes`:

```r
install.packages("remotes")

remotes::install_github("waiteb5/curl")
```

**Important:** This fork uses experimental Windows UCRT bundles targeting libcurl >= 8.23.0. It may differ from the upstream package in bundled dependencies and build configuration.

For the original CRAN package and upstream development, see [jeroen/curl](https://github.com/jeroen/curl).


## Relationship to upstream

This repository is a fork of [jeroen/curl](https://github.com/jeroen/curl).

The upstream project remains the canonical CRAN package. Changes in this fork are focused primarily on experimenting with newer libcurl versions and Windows UCRT binary bundles.

Please report issues specific to this fork through this repository rather than the upstream project.
