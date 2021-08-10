# Top-5-workplace-related-injuries-in-the-US
The main aim of the project is to (1) find out the top 5 severe injuries reported by employers in the US., (2) which states have the highest counts of these severe injuries and (3) who are the employers reporting these highest counts of severe injuries.  

P.S: As I am currently located in the state of Missouri, the injury statistics for that has been added as a bonus.


#The injury dataset was obtained from OSHA (Occupational Safety and Health administration). Link:https://www.kaggle.com/jboysen/injured-workers#:~:text=https%3A//www.osha.gov/severeinjury/index.html

Step 1: CLEANING THE DATA

I created a plot to see which columns had the higest number of missing values and whether those columns were relevant to my Exploratory Data Analysis. The columns - Address 2, Inspection and Secondary Source Title had null values and were not relebant for my analysis. So, these were dropped.
Then the Employers column had certain Employers which are the same but the entry for them as been made under slightly different name. For Example U.S. Postal Service and USPS are the same.
I corrected for those.
Finally, I filtered out the columns which I found most relevant to my analysis: "EventDate","Employer","City","State","Hospitalized","Amputation","NatureTitle","Part of Body Title","EventTitle","SourceTitle".

Step 2: INITIAL STATISTICS

I found out the top 5 injuries, Employers and States by normalizing the data.
This indicated that the top 5 injuries are 'Amputations','Fractures','Soreness, pain, hurt-nonspecified injury','Traumatic injuries and disorders, unspecified' and 'Cuts, lacerations'.

This enabled me to modify the data even further and create a new dataset called 'Final_df2' which contained these severe injuries.

Step 3: VISUALIZATIONS

(1) leading counts of injuries are: 'Amputations','Fractures','Soreness, pain, hurt-nonspecified injury','Traumatic injuries and disorders, unspecified','Cuts, lacerations'

(2) leading Employers are USPS,UPS, Tyson Food Services, Publix and AT&T

(3) Leading states are: "TEXAS",'FLORIDA','PENNSYLVANIA','OHIO','ILLINOIS','MISSOURI' (MO has been added as I am currently located here).

#Top severe Injuries as per employers

USPS is the leading employer in all states and they have reported the highest counts of fractures and soreness,pain,hurt-nonspecifed injury.

UPS is the second leading employer they have high counts of fractures,soreness,pain,hurt-nonspecifed injury and amputations (which is infact more than USPS)

Tyson which is the third largest employer have highest counts for amputations compared to other injury categories.

Publix have high fractures, AMputations and Cuts and Lacerations.

Finally, AT&T have high counts of fractures,soreness,pain,hurt-nonspecifed injury,Traumatic injuries and disorders, unspecified.

#Top severe Injuries as per State

Fractures are the highest for Florida followed by Texas.

Soreness,pain, hurt-nonspecified injuries are the highest for Texas followed by Illinois.

Illinois had the highest Traumatic injuries and disorders, unspecified.

Amputations in Missouri are higher than the top 5 states.

Florida has the highest cuts and larcerations.

Few more graphs have been created to show breakdown of injuries and hospitalizations by State and Employers.
