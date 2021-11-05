# <p align="center"> 📈 Using Tableau Public to Visualize Climate Data 📈 | 📍 Thursday 4 of November at 18:00h CET
            
< align="center"> Fast index: [Intro](#a-bullet) | [Content](#b-bullet) | [Resources](#c-bullet) | [Challenge](#d-bullet) </div>
            
# :hourglass_flowing_sand: Intro <a name="a-bullet"/>
Analyzing data is crucial for society to best come up with solutions to the various environmental and societal challenges we face 🎯. Without it, the latest IPCC (Intergovernmental Panel on Climate Change) report, for example, wouldn’t be possible.

We’ll use Tableau Public to explore what effect the COVID-19 global lockdown had on air pollutant levels during the first quarter of 2020.

📌 The workshop is beginner-friendly! All you need is a computer, a good internet connection and to set up a Tableau Public profile to host your work and be able to use the tool (it’s simple to do and you can download the desktop version [here](https://public.tableau.com/s/)).

# :speech_balloon: Content <a name="b-bullet"/>
This folder contains the materials for the analysis:

1) At the beginning of the workshop you can find the 
[datasets](https://github.com/ang-ferriz/Tableau_Public_Workshop/tree/main/Tableau_Public_Workshop/Datasets) we are working with:
- :globe_with_meridians: Dataset 1 | `dataset1_global_no2.xlsx` (Excel file): global changes of NO2 levels. Edited data to leave only the columns we are interested in for this case. The original dataset can be found in [_Data for: Impact of Lockdown during the COVID-19 Outbreak on Global Air Quality_](https://data.mendeley.com/datasets/wwjnw24xvk/1).
- :chart_with_downwards_trend: Dataset 2 | `data2_filtered.csv` (Comma Separated Values file): some NO2, PM10, PM2,5 data for specific places. The original dataset, which was a really big file with lots of measurements, was edited to make it easier to work with. The Python Jupyter Notebook, [pre_processing_Q12020_data.ipynb](https://github.com/ang-ferriz/Tableau_Public_Workshop/blob/main/pre_processing_Q12020_data.ipynb), with the cleaning steps is available in the repo just to show how the original dataset from the [_Air Quality Open Data Platform_](https://aqicn.org/data-platform/covid19/) was filtered.
            
2) [Tableau link](https://public.tableau.com/app/profile/.ngela4803/viz/Workshop_Live_04Nov/COVID-19AirQualityChanges?publish=yes) for the final dashboard and the file of the Tableau workbook. You can download the file and open it in your local machine.

3) Some of the insights from the visualizations:
            
- :date: The NO2 measurement values during first quarter of 2020 show that lockdown had a positive effect (reduction) on indicators starting from the general variations worldwide and going on detail in Italy as an study case because of the remarkable decrease of pollution indicators levels.
            
- :stop_sign: In Italy the percentage of NO2 comparing 2015-2019 and 2020 was near to -35%, it probably reduced significantly during lockdown due to transport shutdown and low mobility. 
            
- :car: The significant reductions of pollutants levels were clear even though the lockdown still had not started, this could be a signal of the slowdown in the economic activities. As nitrogen dioxide is emitted as a result of fossil fuel combustion processes, mainly from street vehicle activities in urban areas it makes sense that a reduction is shown in the graph.
            
Ready?! Let's go! 🙌

# :books: Resources <a name="c-bullet"/>
Some resources to learn more about the Q&A topics mentioned during the workshop:
            
For visual best practices :bar_chart::
+ [Tableau for Dummies: Tips to Make You Tableau-Smarter](https://www.tableau.com/about/blog/2016/3/5-great-tips-tableau-dummies-51512)
            
- [Visual Analytics](https://www.tableau.com/data-insights/reference-library/visual-analytics)
            
- [Visual Best Practices](https://help.tableau.com/current/blueprint/en-us/bp_visual_best_practices.htm)
            
- [When Visualizing Data, Ask Yourself: Where Are Your Eyes Drawn?](https://www.tableau.com/about/blog/2015/10/where-are-your-eyes-drawn-45392)
            
How to build :top: ranges -- _not so beginner friendly_ but really well explained:
            
- [Sets for Top N and Others](https://help.tableau.com/current/pro/desktop/en-us/sortgroup_sets_topn.htm)
            
# :fire: Challenge <a name="d-bullet"/>
I encourage you continue practising with this little challenge: :computer: Try to reproduce the image below.
            
Hint: build the graphs for the other two pollutants (PM2,5 and PM10), add a text block to the dashboard and the bar plot comparing China (where the pandemic hit first) and Italy. 
            
<p align="center"> <img src="https://github.com/ang-ferriz/Tableau_Public_Workshop/blob/main/goal_dashboard.png" width="800px" height="auto">

You can also try to build a dashboard for another case study (location) to explore the data.

:rocket::rocket: Aaaaaand happy learning, you are doing great!! :rocket: :rocket:
