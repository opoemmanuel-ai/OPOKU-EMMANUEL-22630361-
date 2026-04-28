# Project Title
Regression and Classification with Multi Architecture (Deep) Neural Networks
## Description
The current research analyses models based on the following types of neural networks: deep
neural networks (DNNs), convolutional neural networks (CNNs), long short-term memory
networks (LSTMs), and hybrid networks. For regression analysis, the study utilises the Jena
Climate dataset, while for the image classification task, the MNIST database will be used.
The overall goal of this investigation is to analyse the effect of certain architectural features
of neural networks on their ability to learn.

## How to run
1. Install required packages (see Requirements section).
2. Open the .qmd (Quarto) or .Rmd (R Markdown) file in RStudio.
3. Ensure the dataset paths are correct (Jena dataset and MNIST via Keras).
4. Click *Render* to compile the full report (HTML/PDF).
5. All results, tables, and plots will be generated automatically.

## Requirements
- R version 4.5.3
- Packages used
library(tidyverse)
library(lubridate)
library(corrplot)
library(ggplot2)
library(forecast)
library(tseries)
library(keras3)
library(tensorflow)
## Author
Mr. OPOKU EMMANUEL
