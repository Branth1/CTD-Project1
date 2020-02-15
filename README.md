# CTD-Project1
https://colab.research.google.com/github/Branth1/CTD-Project1/blob/master/ME450Project1F.ipynb
## Description

This is a study of the variances in ocean conditions at 7 different locations during winter and summer. The data has been collected using CTD sensors and is available from the site listed below.

The comparisons to be made will be the changes in SSP during different seasons on approximately the same day as well as the changes over different times of day. The location of these tests and the impact it has on the results will also be taken into account.

It should be noted that although it is ideal to have all data collected on the same day, for some devices this was not possible. In addition, these data sets were selected at random and not all contain an accurate representation of the collection site. The following analysis should be used for reference purposes only. An analysis of more data would be needed to support any conclusions. Please visit the ocean observatories website for additional information regarding the collection of data or to request your own samples. 

## Background

**The questions we are looking to solve are as follows:**

        1-Compare the number of dives per day of the shallow profiler vs the deep profiler.

        2-Where is the maximum value of SSP in each season?

        3-Compare the SSP profile in day vs night

        4-Compare the SSP profile in Summer vs Winter

        5-Compare the SSP profiles of all profilers recorded at same day in summer and winter.

**The devices and dates for recording are as follows:**

Coastal Endurance › Oregon Shelf Surface Piercing Profiler Mooring

                -Summer 08/25/17-08/26/17

                -Winter 11/01/18-11/02/18

Coastal Endurance › Oregon Offshore Cabled Shallow Profiler Mooring

                -Summer 08/23/16-08/24/16

                -Winter 11/07/18-11/08/18

Coastal Endurance › Oregon Offshore Cabled Deep Profiler Mooring

                -Summer 08/20/18-08/21/18

                -Winter 11/01/15-11/02/15

Cabled Array ›Oregon Slope Base Shallow Profiler

                -Summer 08/23/16-08/24/16

                -Winter 11/07/18-11/08/18

Cabled Array ›Oregon Slope Base Deep Profiler

                -Summer 08/20/18-08/21/18

                -Winter 11/07/15-11/08/15

Cabled Array ›Axial Base ShallowProfiler

                -Summer 08/23/16-08/24/16

                -Winter 11/01/15-11/02/15

Cabled Array ›Axial Base Deep Profiler

                -Summer 08/20/18-08/21/18

                -Winter 11/07/18-11/08/18

## Solution/Results

The data was analyzed utilizing the code found in the link above. First the data was imported, the variables needed were defined and the plots necessary were constructed. The resulting plots are seen below.

**Coastal Endurance › Oregon Shelf Surface Piercing Profiler Mooring**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df1time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df1ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/dfs1time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/dfs1ssp.png)

**Coastal Endurance › Oregon Offshore Cabled Shallow Profiler Mooring**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df2time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df2ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df2stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df2sssp.png)

**Coastal Endurance › Oregon Offshore Cabled Deep Profiler Mooring**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df3time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df3ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df3stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df3sssp.png)

**Cabled Array ›Oregon Slope Base Shallow Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df4time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df4ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df4stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df4sssp.png)

**Cabled Array ›Oregon Slope Base Deep Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df5time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df5ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df5stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df5sssp.png)

**Cabled Array ›Axial Base ShallowProfiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df6time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df6ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df6stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df6sssp.png)

**Cabled Array ›Axial Base Deep Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df7time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df7ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df7stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df7sssp.png)

## Conclusions
From the analysis conducted, the following conclusions were made:

1. Comparing the # of dives per day for the shallow profiler in winter it has about 2 if we count the half dive and summer it has 4. For the deep profiler it has 12 in winter and about 2 in summer. It is important to note that some of the data sets may not have collected during the entire 24 hour period. In addition, the deep profiler data in winter does not encompass an entire dive as seen by the small range of the y-axis.
2. In the summer we find the maximum average SSP at Cabled Array \&gt; Oregon Slope Base Deep Profiler. In the winter the max average SSP is found to be at the Coastal Endurance \&gt; Oregon Shelf Surface Piercing Profiler Mooring. The deep profiler in summer is as expected, having some of the deepest waters on that dive and warmer temperatures would correlate to a maximum SSP. However, the surface profiler found in winter is unexpected. We would assume that at the surface there would be a slower SSP than at very deep waters. 
3. When comparing the SSP profile for day and night, this is slightly tricky to do since we have to account for the dives in this analysis. The SSP experiences much greater variations from the changing depth than it does from the time of day. However, if we look at the same depth at night and day, a slight variance is noticed. 
4. Looking at the SSP profile for all profilers and comparing between winter and summer it would be expected that the profiles would have greater values in the summer due to the increased temperatures. This can be seen by the steeper slope visible in the winter graphs.
5. It was attempted to find the average SSP profiles recorded at the same day in summer and winter for all profilers. However, some profilers only recorded during certain days, years, hours, etc. Due to this, the data was selected as closely as possible to the same day of month and the year may vary. Even with this variation, the average SSP for all profilers fit within a relatively small range of 1480-1491. The Oregon slope shallow and Oregon shelf surface profilers appear to have the highest SSP values independent of season.

## References

Data was downloaded from:
https://oceanobservatories.org
