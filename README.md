# EU ETS Emissions vs Carbon Price: Did Higher EUA Prices Drive Emissions Reductions?


**Research questions**
- How did emissions and emissions reductions trends differ across EU ETS covered sectors ?
- Are reductions driven by allowances prices ?


**Data sources**
- GHG Emissions : european environmental agency (EEA) (dataset: European Union Emissions Trading System (EU ETS) data from the Union Registry)
  - Sectors : Power, Industry, Aviation , other minor sectors combined 
- EUA prices : From 2005 to 2008 : ICAP,From 2009 to 2023 : European Central Bank ( dataset: Capital markets-Carbon price-EU allowance per metric ton - Winter/March 2024, Euro area, Annual  


**Methodology**
 - Import datasets
 - Inspect and clean datasets
 - Merge EUA prices data with EU ETS emissions data
 - Generate summary table
 - Visuals

**Key outputs**
  - Visual displaying emissions trends across sectors and EUA prices over the years
  - Visual illustrating sectoral emissions reductions compared to EUA prices fluctuations 

**Key findings**
- Power and industry are the dominant emitting sectors throughout, while aviation and other minor sectors contribute relatively low or near-zero emissions.
- Emissions decline is driven primarily by the power sector, whose emissions fall by nearly half between 2005 and 2023, whereas industry emissions fluctuate but remain broadly stable over the period.
- Year-to-year emissions changes are mostly positive between 2005 and 2012, particularly in the power sector, followed by sharp and sustained declines from 2013 onward across all sectors.
- EUA prices remain low and volatile until 2019 and increase sharply only after 2020, meaning that the main emission reductions precede the sustained price increase, indicating no clear contemporaneous correlation between emissions changes and EUA price levels.












**Policy insights**

- The substantial decline in power-sector emissions observed from around 2012 coincides with the transition to Phase III of the EU ETS, when the cap became EU-wide and auctioning replaced free allocation as the default. With nearly 100% auctioning in the power sector, carbon price signals were strengthened, reinforcing incentives for emissions reductions.
- Over the study period, the industrial sector did not exhibit substantial emissions reductions, suggesting that extensive free allocation of allowances—introduced to mitigate carbon leakage risks—may have weakened decarbonisation incentives.
- EUA prices remained subdued throughout most of the 2010s due to a persistent surplus of allowances, extensive free allocation, and limited confidence in long-term scarcity. Prices began to rise significantly only after structural reforms—most notably the Market Stability Reserve—restored credibility to the EU ETS and tightened expected supply.
- Taken together, these findings point to a nuanced relationship between emissions reductions and exposure to EUA prices, with outcomes strongly mediated by policy design, particularly the balance between auctioning and free allocation, as well as sectoral coverage rather than EUA prices alone.














**Tools and libraries**
- Python
- Pandas
- Matplotlib
