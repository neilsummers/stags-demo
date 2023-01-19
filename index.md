---
title: STAGS
layout: home
nav_order: 1
---

# STAGS
Strategic Technical Analysis for Golf Stats
{: .fs-6 .fw-300 }

## Why develop my own stats tools?
* Own my data outside of current stats apps - avoid vendor lock-in
  * Moving between stats apps means losing historical data and having to start over
* Ability to analyze the data myself and answer questions I have about my game
* Collect more detailed data and incorporate into models

## What is different from other golf stats apps?
* Uncertainty quantification for golf stats
  * Golf stats are mostly quoted without any associated uncertainty
  * This gives little context on how signification any particular result is
  * Focus on providing uncertainty with any stats so can understand what is really changing versus what is just inherent variability of golf
* Proximity to target
  * Apps that track proximity use proximity to hole, but the hole is not my target
  * Track target relative to hole when playing
  * Proximity to target calculated for more accurate shot distributions
* Strategy
  * Stats that help you track your course management
  * Measuring appropriate target selection
    * are you going for too many pins?
    * are you playing too conservatively?
* Adjustments to yardages
  * Elevation, wind, temperature are all factors that I use to select the club
  * Track adjustments to stock yardages during round
  * Track any adjustments for in-between yardages
  * Use these factors when determining effective distance each shot travels when computing club distances
* Club distances
  * Use effective distances correcting for elevation, wind, temperature and gripping down on the club
  * Ability to exclude shots (e.g. recovery, or non-standard shots)
  * Model fit filters out the random variability of shots to obtain stock club distances to use on course
* Course Notes
  * Summary of data that can be used for decision-making on the course
  * Stock yardages for each club
  * Min and max yardages for covering bunkers or staying short of trouble
  * Dispersion for appropriate target selection for tucked hole locations
  * Aim adjustments to help center shot patterns on target
