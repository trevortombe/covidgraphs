---
layout: page
title: Canadian Vaccines by Age
subtitle: Vaccination rates by age and sex
---

Vaccination rates by detailed age and sex are available through the federal government [here](https://health-infobase.canada.ca/covid-19/vaccination-coverage/). This data is released on a weekly basis, normally each Friday, and covers the previous week up to Saturday. To get a sense of daily updated vaccination rates by detailed age categories, I project forward based on a logistic growth model calibrated to match the week-over-week changes in the actual data. The latest results of that estimate is displayed below.

![](Plots/demo_plot_bar_proj.png)

---

The actual data follows, though it features a long lag.

![](Plots/demo_plot_bar.png)

![](Plots/demo_plot.png)

![](Plots/demo_plot_balls.png)

---

Based on the weekly age data, the following presents an experimental estimate of the daily age distribution of doses administered in Canada. Imputation by age is required in early months due to data limitations. Younger individuals vaccined in early phases of the campaign are primarily healthcare workers, although this data was discontinued after April 10.

![](Plots/age_area.png)
![](Plots/age_area_line.png)

