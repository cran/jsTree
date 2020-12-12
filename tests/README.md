Tests and Coverage
================
12 December, 2020 12:22:42

-   [Coverage](#coverage)
-   [Unit Tests](#unit-tests)

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                          | Coverage (%) |
|:--------------------------------|:------------:|
| jsTree                          |    80.49     |
| [R/jsTree.R](../R/jsTree.R)     |    78.57     |
| [R/makelist.R](../R/makelist.R) |    82.50     |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                |   n |  time | error | failed | skipped | warning |
|:------------------------------------|----:|------:|------:|-------:|--------:|--------:|
| [test-html.R](testthat/test-html.R) |   1 | 0.498 |     0 |      0 |       0 |       0 |
| [test-nest.R](testthat/test-nest.R) |   5 | 0.019 |     0 |      0 |       0 |       0 |

<details closed>
<summary>
Show Detailed Test Results
</summary>

| file                                    | context | test                  | status |   n |  time |
|:----------------------------------------|:--------|:----------------------|:-------|----:|------:|
| [test-html.R](testthat/test-html.R#L10) | html    | tree html             | PASS   |   1 | 0.498 |
| [test-nest.R](testthat/test-nest.R#L10) | nest    | nesting default       | PASS   |   1 | 0.004 |
| [test-nest.R](testthat/test-nest.R#L25) | nest    | nesting different sep | PASS   |   2 | 0.008 |
| [test-nest.R](testthat/test-nest.R#L37) | nest    | nesting nodestate     | PASS   |   2 | 0.007 |

</details>
<details>
<summary>
Session Info
</summary>

| Field    | Value                               |
|:---------|:------------------------------------|
| Version  | R version 3.6.3 (2020-02-29)        |
| Platform | x86\_64-apple-darwin15.6.0 (64-bit) |
| Running  | macOS Catalina 10.15.7              |
| Language | en\_US                              |
| Timezone | America/New\_York                   |

| Package  | Version |
|:---------|:--------|
| testthat | 3.0.0   |
| covr     | 3.5.0   |
| covrpage | 0.1     |

</details>
<!--- Final Status : pass --->
