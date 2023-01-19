---
title: Course Notes
layout: default
nav_order: 4
has_children: true
---
# Course Notes
These are the notes from the data that you can take out on the course.

|column| description                                             |
|:-----|:--------------------------------------------------------|
|min   | 80% confidence interval for minimum yardage             |
|fit   | yardage from model fit                                  |
|max   | 80% confidence interval for maximum yardage             |
|disp  | 80% left/right dispersion from approach grouping        |
|aim   | center of shot pattern adjustment from aproach grouping |

{: .note }
The dispersion and aim are calculated per approach yardage range. Will break out per club when more data available.

{: .note }
The quoted 80% dispersion is a one-sided confidence interval. For example the `min` yardage means that 80% of shots go further than this yardage.

## How to use this data
* Different set of yardages based on the temperature which adjusts my real round performance at different temps
* For regular shots to open pins, use the `fit` yardage
* For pins tucked behind bunkers, use the `min` yardage for the distance to carry the bunker
* For back pins or slopes you don't want to go beyond, use the `max` yardage to that point
* For pins tucked near trouble left or right, use the `disp` yards for the amount to aim away from that trouble
* For pins close to edge of green by somewhat easy up and down, make sure `disp` yards contains at least ½ green
* Use `aim` to adjust your mental aim left (negative) or right (positive) of your actual target
* When in between yardages, use the `yards/inch` from the model to grip down on the club to take yards off
