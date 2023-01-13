# Surfs Up Analysis

## Overview of the statistical analysis:
The purpose of this analysis is to provide potential investors of a Hawaii-based "surf-and-shake" shop with additional information about weather trends that could impact the popularity of the business throughout the year.

## Results:
The table below displays the summary statistics of the observed temperatures for the month of June:

<img width="168" alt="image" src="https://user-images.githubusercontent.com/114873837/212202563-e87bfd73-f8fd-4092-810a-4240a7ed9518.png">

The table below displays the summary statistics of the observed temperatures for the month of December:

<img width="147" alt="image" src="https://user-images.githubusercontent.com/114873837/212202674-a38c75fd-2489-486c-91ce-2a49764f1b0a.png">

From these summary statistics tables, we can see a few differences in weather between June and December, including:
- December has colder temperatures than June. This finding is not surprising, as Hawaii's weather still follows a seasonal pattern. However, even winter "cold" never gets TOO cold, as the minimum temperature observed in all December datapoints was 56 degrees - By comparison, climate research conducted by the National Centers for Environmental Information in 2020 estimates the national average minimum temperature for December to be 24.8 degrees (https://www.ncdc.noaa.gov/sotc/national/202012).  
- December's temperatures vary more widely than June's. This is reflected in the larger standard deviation, a lower minimum temperature, and a similar maximum temperature. In December, visitors and residents should expect less consistently warm temperatures than they would in June, though experiencing a true "cold snap" is extremely unlikely.  
- The June list of measured temperatures has more data points (1700 observations) than the December list (1517). It would be helpful to explore the data further in order to better understand the reason behind this discrepancy. Did some weather stations shut down over the holidays? Was there a weather event that knocked a station offline? Was the data for a particular year incomplete or missing? Knowing the answers to these questions would allow us to rule out any factors that could skew our analysis. 

## Summary:

Despite the wider range of temperatures that may be experienced in December, including temperatures on the coolest end of the range (in the 50s), Hawaii's mild year-round temperatures and relative warmth in comparison to the mainland makes it a popular vacation spot for those seeking refuge from the cold - The "surf-and-shake" shop would be well-positioned to capitalize on these trends. In order to optimize the location of the stand, I would recommend further exploration into the following data:

1.) While temperature observations can give us a good sense of ice cream sales and general popularity of outdoor activities, there are other weather-related factors that may impact behavior of surfers specifically. I would run this same analysis replacing temperature observations with wind speeds, or even incidents of winter storms within a certain mile radius, both of which would impact the types of waves that may provide favorable surfing conditions.
2.) While the summary statistics table provides a general overview of major trends between the summer and winter months, it may be helpful to break the monthly data down further into increments like days or weeks, so we can get a better sense of how the weather may shift as the month progresses. For example, is the last week of June much hotter than the first week, which may forecast an uptick in ice cream sales? This would be helpful information to know for purposes of planning inventory orders and staffing. 
