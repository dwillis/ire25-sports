# Storyball: Finding ideas in sports data

### Derek Willis, University of Maryland

#### <https://github.com/dwillis/ire25-sports>

### Getting Started

If you have a GitHub account, you can fork this repository to make your own copy of it. If you don't, you can click on [this link](https://github.com/dwillis/ire25-sports/archive/refs/heads/main.zip) to download the entire repository to your computer and open it there using RStudio.

### Resources

-   [Sports DataVerse](https://sportsdataverse.org/)
-   [Sports Data Analysis and Visualization](https://www.thescoop.org/sports/)
-   [Using R Packages to get data](https://www.thescoop.org/sports/usingpackages.html)

## The Fall of Girls Basketball (and Rise of Volleyball)

The past five years has seen an explosion in the popularity of women's basketball: athletes like Aja Wilson, Caitlin Clark, Breanna Stewart, Angel Reese and Paige Bueckers have become internationally famous. You might think that would coincide with an upsurge in girls playing high school basketball. That's not what the data says, and it suggests some potential stories that you could localize. We'll use high school participation data from the National Federation of High School Associations to compare basketball and volleyball, both nationally and on a state-by-state basis. Open the `nfhs.Rmd` notebook in this repository to get started.

Here's one more reason why this matters: with fewer American girls playing high school basketball, the percentage of international athletes playing college basketball in the U.S. is on the rise. But [they aren't typical students](https://www.washingtonpost.com/sports/2025/06/07/harvard-international-athletes-trump/?pwapi_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJyZWFzb24iOiJnaWZ0IiwibmJmIjoxNzQ5MjY4ODAwLCJpc3MiOiJzdWJzY3JpcHRpb25zIiwiZXhwIjoxNzUwNjUxMTk5LCJpYXQiOjE3NDkyNjg4MDAsImp0aSI6Ijg2Y2Y0ZDZiLWJlY2QtNDMzMS05MzhmLWM1MGM2Zjc0ZjQzNCIsInVybCI6Imh0dHBzOi8vd3d3Lndhc2hpbmd0b25wb3N0LmNvbS9zcG9ydHMvMjAyNS8wNi8wNy9oYXJ2YXJkLWludGVybmF0aW9uYWwtYXRobGV0ZXMtdHJ1bXAvIn0.iEiAVsFTiRKqU2QhXe0JCd1dE_Nos83bUOb1ZjeVkJY).

## Investigating the Refs

### Walkthrough: NBA Last Two Minute Analysis

-   [NBA Officiating Last Two Minute Reports](https://official.nba.com/2024-25-nba-officiating-last-two-minute-reports/)

In this repository you'll find a notebook called `nba_two_minutes.Rmd`. Click on it and we'll go through some of this data, make some charts, and talk about the possibilities.

### Walkthrough: Women's College Basketball Officials and Fouls

-   [College Basketball Referee Logs](https://blessyourchart.shinyapps.io/cbb-ref-logs/)

In this exercise, we'll load data from women's college basketball games from the 2024-25 season, including information on which officials worked each game. Let's start with the `wbb_officials.Rmd` notebook. Then we'll turn towards foul calls, using the `wbb_fouls.Rmd` notebook.