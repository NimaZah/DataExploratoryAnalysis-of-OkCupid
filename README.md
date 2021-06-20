# DataExploratoryAnalysis-of-OkCupid
# For data manipulation and tidying
library(dplyr)
library(lubridate)
library(tidyr)
library(tidyverse)

# For data visualizations
library(ggplot2)

# For modeling and machine learning
library(caret)

# Import the data 
Ok <- read.csv(file.choose())
head(Ok)
