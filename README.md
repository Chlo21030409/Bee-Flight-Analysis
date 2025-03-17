# Bee Flight Analysis
R code to manipulate raw data output from raspberry pi into analysis-ready data set for subsequent analysis

<h2>Description</h2>
This project consists of an R script that took a raw data output from a raspberry pi into an csv file that was suitable for subsequent downstream data cleaning, manipulation and analysis. The experiment measured the flight distance, duration and velocity of bumblebee flight from a multiple tethered flight mills running simultaneously. Bees were allowed up to three stops before their flight was terminated. This R code was developed to remove any stops and breaks in the data to enable clean and easy analysis of the data to determine the mean distance, duration and velocity of flight, and perform further statistical analysis to answer the scientific hypotheses of the project.
<br />


<h2>Languages and Utilities Used</h2>

- <b>R</b> 

<h2>Environments Used </h2>

- <b>R studio</b> 

<h2>Programme walk-through:</h2>

<p align="center">
Uploading the raw files: <br/>
<img src="https://imgur.com/OyquqyV.png" height="80%" width="80%" />
<br />
<br />
Selecting cut off time for flight to 2 hours:  <br/>
<img src="https://imgur.com/Ljs6R2f.png" height="80%" width="80%" />
<br />
<br />
for loops to identify stops in flight and remove the 5 rows of data around a stop: <br/>
<img src="https://imgur.com/udtYGKg.png" height="80%" width="80%" />
<br />
<br />
After a third stop flight will be terminated: <br/>
<img src="https://imgur.com/DnlO1Iq.png" height="80%" width="80%" />
<br />
<br />
Calculating distance flown (m), duration and mean velocity of flight: <br/>
<img src="https://imgur.com/RqLL2tg.png" height="80%" width="80%" />
<br />
<br />
Create new dataframe with data outputs: <br/>
<img src="https://imgur.com/JIPIjQB.png" height="80%" width="80%" />
<br />
<br />
Write new dataframes for each mill for further analysis: <br/>
<img src="https://imgur.com/Grb7eLv.png" height="80%" width="80%" />
<br />
<br />


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
