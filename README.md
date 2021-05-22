rm(list=ls())

library(dplyr)
library(tidyverse)
library(lubridate)
library(ggplot2)
library(zoo)



dados23 = read.table("https://raw.githubusercontent.com/ibiri/Ind-stria/main/Produ%C3%A7%C3%A3o_f%C3%ADsica_da_ind%C3%BAtria.txt", h=T, sep="\t",dec=",")
view(dados23)
