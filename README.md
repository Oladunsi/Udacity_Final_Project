# (Ford GoBike System Data)
## by (Oke Oladunsi)

## Dataset

> [Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of [This dataset includes information about individual rides made in a bike-sharing system covering the Francisco Bay area of travels for the month February year 2019](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv) for February 2019 alone in CSV format covering the greater San Francisco Bay area, also available [here data for other cities](https://www.google.com/url?q=https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems&sa=D&source=editors&ust=1658866159905425&usg=AOvVaw1qw9vVQEFEiyG4jAwGQx1H).


## Summary of Findings

### The structure of your dataset.

> I started out just to finish my nanodegree program but as I began to explore, the dataset started to reveal intresting insights to me hence the listed points were noted:
> *  The duration_sec is not normally distributed but skewed. Then I create new feature travel_minutes to enable me observe it more closely which shows that the majority of the members do not use bike share for their trips, and most were around 25 to 40 years old. Most rides were quick and short, that lasted between 5 to 20 minutes, though some riders travel time is close to 23hrs which is not normal.
> *  There is significant difference in the avagrage time travel by customer(13mins) and subscribers(8mins). where is seems subscribers tend to know where they going hereby reducing travel time.
> * the riding patterns between young riders and older riders can both be similar and at the same time be different, depending on the feature selected as microscope.


### Features in the dataset that were helpful during my investigation into the feature(s) of interest selected above.

> `member_birth_year`, then I created new features from the dataset like `Minutes`, `Hour`, ` Year`,  ` Month`, ` Time of Day`, ` Period of Day `,  ` age` e.t.c 



## Key Insights for Presentation

> The duration_sec is not normally distributed but skewed. Then I create new feature travel_minutes to enable me observe it more closely which shows that the majority of the members did not use bike share for all of their trips, and most were around 25 to 40 years old. Most rides were quick and short, lasted between 5 to 10 minutes, that some riders travel time is close to 23hrs which is not normal.
> travelTime_hour shows that 99% of rides are within 1hr and about 91% of these rides are within 20mins. there are some features that have unusual distributions like the ages of rides that holds a values of 141 years that seems odd.
> Most Users don't like to share their rides.
> * There is significant difference in the avagrage time travel by customer(13mins) and subscribers(8mins). where is seems subscribers tend to know where they going hereby reducing travel time.
> * Female riders tends to spend more time riding than other gender
> * People travel time from monday through thursday are within 10 mins but on friday and saturday the avg time goes above 10 mins which occassionaly goes above 15 min but not more than 17mins. Yet during the weekends we have some rides that goes beyond 17mins int 20mins
> * The busiest hours are pretty much consistent throughout the month with rush hours occuring around 8AM and 5PM.
> * Wednesday is the day the ride service is used the most and during the weekend there is a constant reduction of usage.
> * That dataset also shows that even though all genders incresed their travel time during weekend male riders travel time reduces by saturday
> * older customers tend to reduce time spent riding during weekends on like youth customers but older subcribers spend similar duration of time younger 
subcribers spend during weekend.
> older customers tend to spend far less time riding during weekends on like youth customers but older subcribers spend similar duration of time younger 
subcribers spend during weekend.<br/><br/>
> looking at people where ages >60yrs other gender spend less time riding from thursday-friday than other genders where male users i.e (sat-sun) looks exactly like that of the younger male users both female users spend more time riding from wednesay- Friday.
> older Female riders tend to spend more time riding than male riders.

