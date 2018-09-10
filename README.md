# testrepo
Hi, This my data science profile
```{r , echo=TRUE}
subject <-c('computer programming', 'math', 'statistics', 'machine learning','domain expertise', 'communications', 'presentation skills', 'data visualization')
rank <-c(2,4,4,2,4,4,4,4)
johnny <-data.frame (subject,rank)
johnny
library(ggplot2)
ggplot (johnny, aes(x=subject, y=rank))+ geom_bar(stat="identity")
```