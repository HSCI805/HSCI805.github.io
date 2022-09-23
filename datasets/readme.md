## Under ```opensource``` folder

```
 library(readr)
# ?readr_example
df<- read.csv('https://raw.githubusercontent.com/HSCI805/HSCI805.github.io/main/datasets/opensource/boneden.csv')
head(df,3)
```


```
$ df=read_csv('https://raw.githubusercontent.com/HSCI805/HSCI805.github.io/main/datasets/wsg.csv', show_col_types = F)
```

```
$ df=read_csv('https://raw.githubusercontent.com/HSCI805/HSCI805.github.io/main/datasets/LungCapData2.csv', show_col_types = F)
```

## IO

```
library(haven)
childIQ<-read_dta( 'https://github.com/medewitt/introduction_to_r/blob/master/data/child.iq.dta?raw=true')
head(childIQ,3)
```


```
inchbio <- read.csv("https://derekogle.com/IFAR/scripts/inchBio.csv", header=TRUE)
```


## R ```utils``` library

[Some datasets available in R](opensource/R_datasets.md)

## Other sources

### Mortality

- http://epidemiology.mit.edu/; e.g.  
  - http://mortalityanalysis.mit.edu/JTxt_data/All/Cervical%20Cancer.xls
  - http://mortalityanalysis.mit.edu/JTxt_data/All/Lip%20Cancer.xls
  - http://mortalityanalysis.mit.edu/JTxt_data/All/Lung%20Cancer.xls
  - More details maybe found in thesis https://dspace.mit.edu/handle/1721.1/45459

### RNA

https://github.com/hbctraining/Intro-to-R-with-DGE/tree/master/data
- counts.rpkm.csv
- mouse_exp_design.csv
- normalized_counts.txt


### HIV

#### WHO-HIV
http://www.who.int/hiv/data/profiles/en/
http://apps.who.int/gho/data/view.main.22100?lang=en
http://www.who.int/hiv/data/2017_summary-global-hiv-epidemic.png?ua=1

#### UNICEF HIV
https://data.unicef.org/topic/gender/gender-and-hiv-aids/
https://data.unicef.org/topic/hivaids/global-regional-trends/
https://data.unicef.org/resources/dataset/hiv-aids-statistical-tables/

#### World Bank Data
http://databank.worldbank.org/data/source/world-development-indicators
