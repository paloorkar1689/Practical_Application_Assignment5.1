# Practical_Application_Assignment5.1
"Will a customer accept the coupon?"

Files included:
README.md --> contains the brief info about the code
prompt.ipynb --> actual code in jupyter notebook
images --> saved bar plots generated from the pattern understanding.
data --> original csv data file


Details:

Business Understanding : The objective of this excercise is to determine based on the data wether the customer
                         will accept the coupon or not. This data can be very useful for future customer enagegement
                         and actions to be taken by the company for more sales. 

Data Understanding: The dataset has 26 columns and 12684 entries. The acceptance column Y is marked 0 for rejection
                    and 1 for acceptance. Various other useful columns have been provided such as type of coupons, driving conditions,
                    weather, history of visits and so on. 

Data Preperation: To analyze the result first we collected empty datapoints. Based on the frequency we either dropped them or replaced with
                  most common datapoint from that column

Modeling: Several Bar plots, queries, histgrams, and percentage acceptace calculations were made to determine the pattern for modeling.


SUMMARY:
   1) General Acceptance rate of coupons is 56%. This is a good identifier telling that better steps need to be taken to target the drivers
      who did not accept the coupons.
   2) When categorized against the type of coupons, highest acceptance was with the Carry out and Restaurants <20 as economical and fast. 
      on the other hand bar coupons had the lowest acceptance rate hence more analysis in the bar specific data needed.
   3) When concentrated on number of times driver visited Bar it was evident that more number of visits will tend to attract more coupon acceptance
   4) When number of visits kept as >1 and tried with several identifiers it was deduced that Driver with age >25 tend to accept the bar coupons better
      and Also if the driver has passanger that are not kids.
   5) Acceptance rate for BAR is not co-related with the income or occupation
