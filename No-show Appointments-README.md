# Investigate a dataset project - No-show Appointments 
The project involves data wrangling and exploratory data analysis 
The No-show Appointments dataset collects information from 100k medical appointments in Brazil
it focuses on the question of whether or not patients show up for their appointment.
## Questions driving the analysis
1. What is the likelihood of patients showing up for scheduled appointment?
2. What is the ratio between genders?
3. Does No-show count have a correlation with Gender?
4. What is the age distribution of the patients?
5. Are schorlarship patients more likely to turn up for appointments?
6. Does No-show count have a correlation with receiving SMS?
7. Do alcoholics skip their scheduled appointments?
## Data Wrangling
Find dulpicates 
find unique data values
Rename incorrect column names
Convert ScheduledDay and AppointmentDay from 'object' type to 'datetime64[ns]'
## Exploratory Data Analysis
1. No_show/Show distribution 
2. Gender Distribution
3. Bar graph showing distribution Show/ No_show based on gender
4. age distribution
5. Scholarship Distribution
6. Bar graph showing distribution Show/ No_show based on sms_received
7. Alcoholism distribution
## Conclusions
1. Over 80% of the patients attend their scheduled appointment.
2. The highest number of patients are of age group 0-10 years.
3. 'Gender' is does not play a role in determining if a patient will show up for the appointment or not.
4. Higher percent of patients with scholarships attend their scheduled appointment
5. Since a higher number of patients that did not receive the SMS showed up for their scheduled appointment, its unclear what kind of message is sent to the patient.
6. Most Alcoholics show up for their Scheduled appointments.

