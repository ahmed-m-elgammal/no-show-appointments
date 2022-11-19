# No show appointments

## Description
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Problem
What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? 

## Solution
> Importing && cleaning data to make it easy to understand and analysable.
> Apply Bivariate && Univariate analysis.

## Conclusions

> After analyzing that data, I found that there is no relationship or correlation between the elements and the non-attendance, and the drawing shows the low correlation between all the elements and the non-attendance.

> The time difference between the date of registration and the date of attendance does not affect attendance

> Most of the patients attend, and the majority of them are women

## Limitations
> Unique Patients are 62,299 out of 110,527

> Appointment days are set between 29/04/2016 and 28/06/2016

> Data is collected from 81 Neighbourhoods

> The effect of location (neighbourhood) on medical appointment atteandance was not examined.

## Reference
> Pandas docs

> Stack overfolw on how to understand the heatmap


### Dependencies

* Python >= 3.6 libraries pandas and numpy and matplotlib and seaborn 
* ex. Windows 10

### Installing

* pip install pandas
* pip install numpy
* pip install matplotlib
* pip install seaborn


## Authors

contact info

ex. [@me](https://www.linkedin.com/in/ahmed-m-elgammal/)
