# Inflation-and-Attention-Thresholds
Replication package for Inflation and Attention Thresholds

The .zip file contains the code and data necessary to generate the results from the paper.

Open the Inf_Att_Rep.do file and set the appropriate directory.
You you also need to have the xthreg package installed to run some of the code

After this, you should be able to run the .do file in its entirety.

This .do file was run on STATA version 16.0
And the R script in referenced in 7. was run on RStudio version 2023.06.1+524

The replication package includes the following data files:

1. Google_Hits.dta contains data for 38 countries retrieved from Google Trends. The search data was pulled for the relevant languages for each country (see article for more details). We retrieved this data in the summer of 2022. The other main variable in the data set are monthly inflation rates. This data was retrieved from the OECD.

2. Twitter_Dat.dta contains the monthly share of “inflation” Tweets for the 15 countries we analyze. See paper for more details about the data construction.

3. News_Dat.dta contains the monthly share of “inflation” newspaper articles for the six countries we examine for contemporary data. See paper for more details about the data construction.

4. Hist_US_News_Dat.dta contains the historical monthly share of “inflation” newspaper articles for The NY Times and WSJ. See paper for more details about the data construction.

5. Habit_Dat.dta contains the data underlying Figure 4 in the main text. This is just plotting some of the regression results generated when running the individual country regressions in the main part of the .do file

6. Hist_Dat.dta contains the data underlying Figure A.3 in the Appendix.

7. BetaPlot.csv and BetaPlotPost2010.csv contain the data to generate Figure 2 in the main text and Figure A.4 in the Appendix, respectively. To construct these plots run the R script “BetaPlotScript.R”

