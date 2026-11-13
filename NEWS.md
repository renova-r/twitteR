# twitteR 1.1.9.9001

Renova release, based on CRAN twitteR 1.1.9 (published 2015-07-29).

- `DESCRIPTION`: added `Authors@R` (Jeff Gentry, aut/cre, same maintainer address) and changed `Author` to `Jeff Gentry [aut, cre]`.
- `man/*.Rd` (`getUser`, `search`, `search_twitter_and_store`, `setup_twitter_oauth`, `showStatus`, `timelines`, `updateStatus`, `use_oauth_token`): `\link{GET}`, `\link{POST}` and `\link{Token}` now point to `httr`.
- `man/retweets.Rd`: removed the placeholder `\keyword{ ~kwd1 }`; `~kwd2` remains. No R code was changed.
- `DESCRIPTION`: `Version` set to `1.1.9.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed. `LICENSE.md` (license text), `README.md`, `NEWS.md` and `.Rbuildignore` were added.
