
# Project 1: SAT & ACT Analysis

## Problem Statement

The objective of this project has been to analyze the SAT & ACT data available for 2017 and 2018. The data comprises of participation rates per state wherever available and the individual state avaerage scores. The data has been cleaned, analyzed and looked for useful information that would help understand why some states prefer one of the two exams.

## Executive Summary

## Data sources

The source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows).

### Contents
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data dictionary

|Column Name|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The state of consideration, e.g. \"Maryland\"|
|---|---|---|---|
|math|float64|ACT|Score on a scale of 1-36 in Mathematics with a minimum possible score of 1.|
|english|float64|ACT|Score on a scale of 1-36 in English with a minimum possible score of 1.|
|reading|float64|ACT|Score on a scale of 1-36 in Reading with a minimum possible score of 1.|
|science|float64|ACT|Score on a scale of 1-36 in Science with a minimum possible score of 1.|
|composite|float64|ACT|Average of the four subject scores on a scale of 1-36 with a minimum possible score of 1.|
|---|---|---|---|
|math|int64|SAT|Score on a scale of 800 in Mathematics with a minimum possible score of 200.|
|reasoning|int64|SAT|Score on a scale of 800 in Evidence Based Reading and Writing with a minimum possible score of 200.|
|math|int64|SAT|Score on a scale of 800 with a minimum possible score of 200.|

## Conclusions and Recommendations

- The key take away from my understanding of the data and some online material is that ACT and SAT exams are administered through state policies which play a big role in the participation rates. 
- Anohter factor that seems to encourage participation is the offer of free preparation sessions or exams which make one test more approachable than the other.