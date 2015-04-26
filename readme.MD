---
title: "Readme"
output: html_document
---

# Getting and Cleaning Data Project: run_analysis.R

#Overview

The file run_analysis.R  completes tasks set by the Getting and Cleaning data Course Project and produces a dataset called "TD.txt".

To Do

Acquire data at https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip and load it into R working directory before executing run_analysis.R


What does the script do?

The script run_analysis merges training and test data into one set. It then extracts mean and standard deviation for each measurement. It utilises activity names to tag activities in the data set. Ultimately it produces a fresh data set according to the instructions of the course project.