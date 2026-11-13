# twitteR

An R interface to the Twitter web API (search, timelines, users, direct messages and local storage of results).

Compatibility updates by Renova.

Version 1.1.9.9001 makes documentation and metadata changes and no R code change. `DESCRIPTION`: the author is also listed in an `Authors@R` entry and `Author` reads `Jeff Gentry [aut, cre]` (maintainer address unchanged). Help pages now name the `httr` package in `\link` targets for `GET`, `POST` and `Token`, and one placeholder `\keyword{ ~kwd1 }` line was removed from `man/retweets.Rd`. The Twitter service that this package talks to may no longer accept its requests.

## Install

From R-universe:

```r
install.packages("twitteR", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/twitteR@renova-1.1.9.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

twitteR was written by Jeff Gentry (maintainer). License: Artistic-2.0 (see [LICENSE.md](LICENSE.md)).
