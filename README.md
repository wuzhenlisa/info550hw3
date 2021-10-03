# Info-550
For my project, I use the data from kaggle, the link is https://www.kaggle.com/uciml/breast-cancer-wisconsin-data. You can download the dataset from kaggle website or from my repo at first and change the data address in the subline,
```{r}
breastcancer <- read.csv("/mnt/e/Emory_study/Info550/breast_cancer.csv")
```

During running the code, you should install packages: reader, table1 and ggplot2 and use these packages 
```{r}
library(readr)
library(table1)
library(ggplot2)
```

## Execute the analysis

To execute the analysis, from the project folder you can run

```{r}
Rscript -e "rmarkdown::render('ZhenWu_Info_HW3.Rmd')"
```
This will create a file called ZhenWu_Info_HW3.html output in your directory that contains the results.
