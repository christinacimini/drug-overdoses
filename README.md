# Drug Overdose Deaths in the US

# Project Overview
For my final project, I decided to look into the increasing rates of drug overdose deaths in the US. In collecting data from numerous sources, analyzing said data using Python, and visualizing the results in Tableau, I explore potential causes of the increasing crisis in the US and propose possible solutions to mitigate the rise in drug overdose deaths.
# Data Collection
To begin my project, I started with The Monthly Provisional Drug Overdose Death Counts report, which can be found as VSRR_Provisional_Drug_Overdose_Death_Counts.csv and reported monthly drug overdose deaths by drug type and year. However, as opposed to simply analyzing patterns in the rates of death, I was interested in exploring which external factors could be influencing the rise in overdoses. To supplement my data, I collected US Census information on poverty, insurance, education and population numbers. It should be noted that there is no Census data from 2020, presumably due to the COVID-19 pandemic. Additionally, I found data on rates of homelessness via the US Department of Housing and Urban Development, which can be found in the Homelessness Data.xlsx file. I also found information on state GDP via the United States Regional Economic Analysis Project, and lastly, I researched individual state laws on the history of marijuana legalization. I combined all of this information into one main Excel sheet which can be found as poverty_insurance.xlsx.
# Data Analysis and Visualization
I then combined my data using Python and created an XGBRegressor model which, in combination with my external data I collected, can predict the percentage of deaths which are accounted for by drug overdoses with 99% accuracy. Additionally, I used Python to check for individual correlations with my additional data to see which external factors do seem to have an influence, or at least a co-occurance, with higher rates of drug overdose deaths. This analysis can be found in the overdoses_cleaned.ipynb file. I then graphed this data in a simple Tableau dashboard, found as Drug Overdoses.twbx, which allows one to see not only the rise in occurances of drug overdose deaths but also the increasing percentage of deaths which were the result of a drug overdose. Additionally, I depict the historical rates of drug overdose deaths in addition to the changing rates of my external data.
# Policy Recommendations
Lastly, I presented my findings in a presentation I completed on Canva, where I propose a number of policy changes that may reduce the rate of drug overdose deaths given their significant correlation.
