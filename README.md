# ENVS-193DS_spring-2025_final

Spring Final Exam :) 

# General Information

This repository is for the spring ENV S 193DS Data and Statistics for Environmental 
Studies final exam. This final exam consists of four questions; each with their 
set of skills that we must demonstrate through our work. We are required to 
demonstrate our ability to identify gaps in statistical communication, visualize
and wrangle data, as well as identify, execute, and visualize an appropriate 
statistical method given a data set. Finally, we use a generalized linear model 
effectively replicating the analysis performed in an ecology study examining the
probability of nest box occupancy for a species of parrot. The last problem 
involves demonstrating our ability to communicate about our affective data 
visualization in addition to designing and executing an appropriate statistical 
analysis of our personal observations from throughout the quarter. 

# Data and File Information 

**Packages:** 

```{r, message=FALSE}

library(tidyverse)
library(here)
library(gt)
library(janitor)
library(readxl)
library(dplyr)
library(MuMIn)
library(DHARMa)
library(lubridate)
library(ggeffects)
library(fs)


```

### Final Exam Problems and Respective Data Sources: 

**Problem 1:** 

Saleh, Dina and Joseph Domagalski. 2021. “Concentrations, Loads, and 
Associated Trends of Nutrients Entering the Sacramento–San Joaquin Delta, 
California.” San Francisco Estuary and Watershed Science. 
DOI: 10.15447/sfews.2021v19iss4art6.

**Problem 2:**

Kui, L. 2024. Daily sea surface temperature in Santa Barbara channel between 
1982 and 2023 ver 3. Environmental Data Initiative. 
https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84.

**Problem 3:**

Stojanovic, Dejan et al. (2021). Do nest boxes breed the target species or its 
competitors? A case study of a critically endangered bird [Dataset]. 
Dryad. https://doi.org/10.5061/dryad.83bk3j9sb

Stojanovic, D., Owens, G., Young, C.M., Alves, F. and Heinsohn, R. 2021. 
“Do nest boxes breed the target species or its competitors? A case study of a 
critically endangered bird.” Restoration Ecology. 
DOI: https://doi.org/10.1111/rec.13319

**Problem 4:**

Personal observation data :)
```
# File Structure:

├── README.md
├── ENVS-193DS_spring-2025_final.Rproj
├── data
│   ├── occdist.csv
│   └── SST_update.csv
|
└── code
    ├── 193DS_final.qmd
    ├── 193DS_final.html
    └── 193DS_final_files
        ├── libs
        |   ├── quarto-html
        |   |   ├── tippy.umd.min.js
        |   |   ├── tippy.css
        |   |   ├── quarto.js
        |   |   ├── quarto-syntax-highlighting.css
        |   |   ├── popper.min.js
        |   |   └── anchor.min.js
        |   |
        |   ├── clipboard
        |   |   └── clipboard.min.js
        |   └── bootstrap
        |       ├── bootstrap.min.js
        |       ├── bootstrap.min.css
        |       ├── bootstrap-icons.woff
        |       └── bootstrap-icons.css
        |
        └── figure-html
            ├── visualizing the model predictions-1.png 
            ├── unnamed-chunk-3-1.png
            ├── model-diagnostics-4.png
            ├── model-diagnostics-3.png
            ├── model-diagnostics-2.png
            └── model-diagnostics-1.png
```            

### Rendered Output: 

The rendered output for the code in this repository is here.


        
        
        


