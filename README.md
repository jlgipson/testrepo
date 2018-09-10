# testrepo
#Hi, This my data science profile code. Grapchis is named JG_DataScience_Profile in testrepo
```{r , echo=TRUE}
subject <-c('comp prog', 'math', 'stat', 'ML','DE', 'Comm', 'Prest', 'DaVis')
rank <-c(2,4,4,2,4,4,4,4)
johnny <-data.frame (subject,rank)
johnny
library(ggplot2)
ggplot (johnny, aes(x=subject, y=rank))+ geom_bar(stat="identity")
```
