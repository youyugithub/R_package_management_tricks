# R_package_management_tricks
```
remove.packages("packagename")
x <- installed.packages(); x[ is.na(x[,"Priority"]), c("Package", "Version")]
install.packages("path/to/package/packagename", repos = NULL, type = "source")
```
