# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
activity <- read.csv("activity.csv")
activity$date <- as.Date(activity$date, "%d-%m-%y")
naClean_activity <- na.omit(activity)
```
## The Histogramm of the total Steps per Day



## What is mean total number of steps taken per day?




## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
