# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
download.file("https://github.com/coryv/RepData_PeerAssessment1/blob/master/activity.zip", "activity.csv")
unzip("activity.csv")
```

```
## Warning in unzip("activity.csv"): error 1 in extracting from zip file
```

```r
activityData <- read.csv("activity.csv")
```

```
## Warning in scan(file = file, what = what, sep = sep, quote = quote, dec =
## dec, : EOF within quoted string
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
