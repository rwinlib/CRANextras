# CRANxtras
CRANxtras mirror using the gcc-4.9.3 toolchain

You can use this mirror by setting `options("repos")` appropriately.

```r
local({
  r <- getOption("repos")
  r["CRANxtras"] <- "https://raw.githubusercontent.com/rwinlib/CRANextras/master"
  options(repos = r)
})
