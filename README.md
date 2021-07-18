# Overview

The purpose of this analysis is to see how much fares each city type (urban, suburban, and rural) are collecting between 1/1/2019 to 4/29/19. We’re looking into what is working for each city type and what is not to optimize fares across each city type.

## Results

Based on our charts, we can quickly access that most fares are coming from urban cities while the least amount of fares is coming from the rural cities. Through out the timeframe we examined, none of the city types experienced large gains or declines. In addition, each city type moved mostly in a similar direction:
<p align="center">
<img src="https://raw.githubusercontent.com/hdolci/PyBer_Analysis/main/analysis/PyBer_fare_summary.png" width="50%" height="50%"/>
</p>

The summary dataframe reveals that Suburabn is the most balanced when it comes to drivers vs ride count. Rural drivers were also able to earn the most possibly due to a shortage of drivers:
<p align="center">
<img src="https://raw.githubusercontent.com/hdolci/PyBer_Analysis/main/analysis/summary_df.png" width="50%" height="50%"/>
</p>

## Summary
Based on the results, these are the 3 areas I recommend we look into further:

1. Look into the increase of fares late February across all city types to see if this is anything we have control over or if it just a seasonal move.
2. Further looking into rural cities at the start of April which was it’s peak during this time frame to see what is driving this.
3. It could be possible not enough drivers for rural (more rides then drivers). This could make Pyber appears to be less reliable and reduce the total fares collected.
