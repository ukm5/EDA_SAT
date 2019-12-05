{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Project 1: SAT & ACT Analysis\n",
    "\n",
    "## Problem Statement\n",
    "\n",
    "The objective of this project has been to analyze the SAT & ACT data available for 2017 and 2018. The data comprises of participation rates per state wherever available and the individual state avaerage scores. The data has been cleaned, analyzed and looked for useful information that would help understand why some states prefer one of the two exams. \n",
    "\n",
    "## Executive Summary \n",
    "I need to figure out how to make these links.\n",
    "\n",
    "## Data sources\n",
    "The source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows).\n",
    "### Contents:\n",
    "- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)\n",
    "- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)\n",
    "- [Exploratory Data Analysis](#Exploratory-Data-Analysis)\n",
    "- [Data Visualization](#Visualize-the-data)\n",
    "- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)\n",
    "- [Outside Research](#Outside-Research)\n",
    "- [Conclusions and Recommendations](#Conclusions-and-Recommendations)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Data dictionary\n",
    "\n",
    "|Column Name|Type|Dataset|Description|\n",
    "|---|---|---|---|\n",
    "|state|object|ACT/SAT|The state of consideration, e.g. \"Maryland\"|\n",
    "|---|---|---|---|\n",
    "|math|float64|ACT|Score on a scale of 1-36 in Mathematics with a minimum possible score of 1.|\n",
    "|english|float64|ACT|Score on a scale of 1-36 in English with a minimum possible score of 1.|\n",
    "|reading|float64|ACT|Score on a scale of 1-36 in Reading with a minimum possible score of 1.|\n",
    "|science|float64|ACT|Score on a scale of 1-36 in Science with a minimum possible score of 1.|\n",
    "|composite|float64|ACT|Average of the four subject scores on a scale of 1-36 with a minimum possible score of 1.|\n",
    "|---|---|---|---|\n",
    "|math|int64|SAT|Score on a scale of 800 in Mathematics with a minimum possible score of 200.|\n",
    "|reasoning|int64|SAT|Score on a scale of 800 in Evidence Based Reading and Writing with a minimum possible score of 200.|\n",
    "|math|int64|SAT|Score on a scale of 800 with a minimum possible score of 200.|"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Conclusions and Recommendations\n",
    "\n",
    "- The key take away from my understanding of the data and some online material is that ACT and SAT exams are administered through state policies which play a big role in the participation rates. \n",
    "- Anohter factor that seems to encourage participation is the offer of free preparation sessions or exams which make one test more approachable than the other. "
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
