# bikesharing
Create our own bike sharing service in Des Moines, IA
## Project Overview
 After the initial presentation for starting a bike sharing service in Des Moines a key investor is looking for more insight and has requested a bike trip analysis.  To meet this requirement we have created additional visualizations and tied them together in a Tableau story.


## Results
The additional analysis has yielded some interesting insights which can be levered in planning the Des Moines startup. 

* Every trip start somewhere and what's clear is some locations will have higher traffic. Space at each location will be limited; backup capacity and refill timing is key to prevent shortages.
    <details><summary>Top Starting Locations</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/Top_Starting_Locations.png)

    </p>
    </details>

* In conjunction with where bikes are rented, when is also important.  Approximately one third of rentals occur in the peak afternoon hours.  Increased staff availability at key locations at peak hours will substantially improve the customer experience and drive repeat business.
    <details><summary>August Peak Hours</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/August_Peak_Hours.png)

    </p>
    </details>

* Rides are generally short in NYC with rides greater than 30 minutes rare.  Thus bikes are available for redeployment fairly quickly.  Estimating ride times in Des Moines based on the city size and density is required.
    <details><summary>Checkout Times</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/Checkout_Times_for_Users.png)

    </p>
    </details>

* There is a large dependence on male renters; this needs to more balanced in Des Moines.   A combination marketing / research campaign should be used to address this.  Essential - what would prompt female riders to rent a bike?
    <details><summary>Checkout Times by Gender</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/Checkout_Times_by_Gender.png)

    </p>
    </details>

* This heat map provides additional details into the Peak Hour chart above.  Weekdays have higher activity, indicating a strong correlation to commuters.  Would Des Moines have a similar profile? 
    <details><summary>Weekday Trips per Hour (heatmap)</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/Trips_by_Weekday_per_Hour.png)

    </p>
    </details>

* This heat map provides further insight into the observation that weekday male commuters dominate the business in NYC.  
    <details><summary>Weekday Trips per Hour by Gender (heatmap)</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/Trips_by_Gender_weekday_per_hour.png)

    </p>
    </details>

* This heat map provides insight into the client type: Subscriber v. Ad-Hoc. The NYC business is heavily dependent on male subscribers.  It is likely Des Moines will need to diversify their client base.
    <details><summary>User Type by Weekday and Gender (heatmap)</summary>
    <p>

    ![](https://github.com/goldbala55/bikesharing/blob/main/images/User_Trips_by_Gender_by_Weekday.png)

    </p>
    </details>



The complete presentation can be found at [Tableau Public](https://public.tableau.com/app/profile/alan.goldberg/viz/BikeTripAnalysis_16254215688020/TheTripDurationStory "CTRL+click to open in a new tab")




Observations:
   * The density, size and life styles of Des Moines will require adjusting the product offering compared to NYC.
   * It is essential to have sufficient bikes available at peak locations at peak hours.
   * Increasing the rentals of female riders and off hour usage will increase profitability.
   * Driving usage on the weekends is another revenue growth area - investigate coordinating rentals with popular events in the city.


## Summary
There is an opportunity to start up a bike sharing service, but the differences between NYC and Des Moines will require a different approach and business model to attain profitability. 

   * Recommended follow up analyses: 
     - Forecast high volume starting points in Des Moines
     - Forecast average ride duration in Des Moines
     - Research and identify opportunities to drive off-hour and weekend usage and co-marketing options.

 ## Resources
 Data: August 2019 [Citi Bike Trip History](https://www.citibikenyc.com/system-data "CTRL+click to open in a new tab")

 Software: Python 3.7.10, Jupyter Notebook 6.3, pandas 1.2.4, Git Bash 4.4.23, Tableau Public 2021.2.0
