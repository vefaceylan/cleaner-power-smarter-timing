# cleaner-power-smarter-timing
Hour-by-hour analysis of Danish grid carbon intensity (2025): shifting a flexible electricity load to the cleanest hours cut its CO₂ emissions by ~40%. Python, pandas, Energinet API.

---------------------------------------------------------------------------------------
In this project, I looked at how clean electricity is in Denmark and whether using electricity at better times can reduce CO₂ emissions.

## What I found

- In eastern Denmark in 2025, running a machine during the cleanest hours of each day instead of at a random time cut its CO₂ emissions by about 40%.
- More renewable energy doesn't always mean cleaner electricity. In 2000, the UK had fewer renewables than Denmark but cleaner electricity, because Denmark used more coal.
- In spring and summer, the dirtiest hours were around midday. I haven't found out why yet.

## What I did

1. Compared Denmark and the UK from 2000 to 2024 using data from Our World in Data.
2. Downloaded 5-minute CO₂ data for eastern Denmark in 2025 from Energinet's API.
3. Checked the data for missing values. About 0.6% was missing, which I left out.
4. Made a heatmap showing the cleanest and dirtiest hours of the year.
5. Compared the CO₂ from running a machine at different times of day.

## Tools

Python, pandas, Matplotlib, Google Colab, Tableau

I also rebuilt the heatmap on Tableau to practise using a BI tool. 
[You can view it here:](https://public.tableau.com/app/profile/vefa.ceylan/viz/CleanerPowerSmarterTiming/Heatmap)

## Data

- Energinet, Energi Data Service: CO2 Emission dataset (CC BY 4.0)
- Our World in Data, Energy dataset, based on Ember and the Energy Institute's Statistical Review of World Energy (CC BY 4.0)
