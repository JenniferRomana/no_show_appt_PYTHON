# Analysis of No-Show Appointments
Why do patients miss their scheduled appointments?

Missed appointments lead to inefficient use of medical practitioners' time,
disruption to the clinic workflow, increased waiting periods
and can hinder optimal care.

This project analyzes and explores the factors that may contribute to a patient
not showing up to a scheduled medical appointment.

### Dataset
There are 110,527 records, each of 14 columns  containing appointment information from Brazil.
The dataset can be found at [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments)

### Questions that will be explored are:
1. Do certain age groups or genders tend to miss appointments?
2. Are appointments more likely missed on certain days (just before or
after the weekend)?
3. Does longer lead-time (the time between the day the appointment is scheduled
and the actual appointment date) correlate with higher incidence of no-shows,
maybe due to forgetfulness or recovery
4. Do sms reminders help lower the incidence of no-shows?
5. Are welfare holders likely to attend an appointment for fear of
possibly losing welfare entitlement due to too many missed medical appointments,
or are non-welfare holders more likely to attend an appointment as they would
possibly have to pay a no-show fee out of their own pocket.
6. Could a patient's physical traits affect their ability to show up to their
appointment?  Are patients with handicaps or suffering from alcoholism more
likely to be a no-show due to inability and incapacity to attend their appointment?

### Conclusions

The factors that seem to have some relation to whether a patient attends or
doesn't attend a scheduled appointment are:
* The lead time between scheduled and actual appointment, with longer lead time
of 1 week and greater displaying a higher level of no-shows. Strategies that
might lower this rate could be explored, however the analysis on sms receipt in
this project concluded that sms reminders had no effect on whether a patient
would attend their appointment. How Sms is used, such as how far in advance they
were received or whether a reply was required could be explored.
* Age groups to a certain extent, with young children under 5 having a higher
attendance rate and teens-early 20s having a lower attendance rate. Appointment
rates were generally higher for the under 5's and could therefore warrant
further resources allocated to these services.
* Enrollment in the welfare program showed a slightly higher rate of no-shows.
Evidence could not be found to support the hypothesis that welfare holders are
on longer wait lists for appointments thus this result could be skewed by
'lead-time' effect
* Physical traits hypertension and to a lesser extent handicap.
* Gender, the weekday of the appointment, diabetes and alcoholism did not show
any relationship with no-shows in this analysis.


### Limitations
* Differences were not tested for significance, such as for hypertension,
handicap and welfare
* 100k+ unique appointments, for only approximately 62k unique patient id's over
a range of 27 appointment days, which averages to just under 2 appointments per
patient. Weeding out the partial duplicates were beyond my capabilities and
therefore all remained in the dataset


### Further Investigation
* It is beyond the scope of this project to analyse the correlation of the
81 neighbourhood and appointment no-shows. It would be interesting to group
these neighbourhoods further, perhaps by region or socio-economic to determine
any trends. Factors such as public transport, parking and even signage or
facilities at the hospital could contribute to a missed appointment.
* A cross analysis of factors could uncover more insights. Such as analysis of
neighbourhoods and accessibility of hospital and clinics for those with handicaps
* Further analysis could be made on the likelihood a patient is a no-show given
that they were previously a no-show. Would the second appointment more likely
be attended?
* Further work on this topic could explore whether initial or follow up
appointments are more likely to be missed.



This project was completed as part of the Udacity Data Analyst Nanodegree
