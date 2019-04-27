### Install from GitHub with
```r
# install.packages("devtools")
devtools::install_github("frycast/studentlife")
```

Details on the dataset are available [here](https://studentlife.cs.dartmouth.edu). Once installed, you can download and extract the data within R:

```
d <- "studentlife"
library(studentlife)
download_studentlife(dest = d)
```

Then you can use the interactive menu to browse the schemas:

```r
studs <- studentlife::load_SL_tibble(location = d)
```

For more information see the help files:

```r
?download_studentlife
?load_SL_tibble
```




