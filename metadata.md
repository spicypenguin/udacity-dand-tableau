Baseball data analysis - Udacity
====================

Links
---------------------

* [Link to v1](https://public.tableau.com/profile/jeff.sinclair#!/vizhome/baseball_hr_average_v1/Dashboard1)
* [Link to final](https://public.tableau.com/profile/jeff.sinclair#!/vizhome/baseball_hr_average_v1/Story2)

Summary
---------------------

* My data visualisation explores the relationships that exist between a players batting average, their number of home runs to their height and which hand they preferred to bat with.
* I wanted to explore the data to see if there were any significant outliers in the information found and visualise any relationships that existed
* From this analysis I have noted that shorter batters seem to have a raised batting average than taller batters (on average), and a higher batting average does not directly correlate directly with more home runs (there is a ceiling)
* Also looking at the data purely based on the absolute number of homeruns can paint an incorrect picture of the performance of left handed vs. right handed batters - in general left handed batters fare better in home run performance than right

Design
---------------------

* Initial design thoughts were to try and map the relationship between the various elements using a series of bar charts and scatter plots - segmenting data by height and handedness where appropriate to show the distinction between the groups
* I chose to use a scatter plot to explore the relationship between home runs and batting average as it would allow both elements to be visualised simultaneously. In additon, I used colour encoding to differentiate between which hand the batter used
* I used the same colours in the bar chart above to show the distribution of data by height and batting hand - to give the viewer familiarity between the two graphs
* I chose to add actions to highlight the selections of users on the dashboard so they could see the selection from one graph visualised in the other
* In the reboot (post feedback), I chose to add additional side-by-side bar graphs to give more context to the data and show how each category performed relative to each other (e.g. how left handed batters performed compared to right handed batters)
* The treemap I think adds a visual element to the overall distribution of homerun data, with large visual impact showing the distribution of batters and their respective home run counts - the colours here also carry through from all the other charts
* In the comparative bar charts where the batting hand was shown side-by-side, I used colour to give a visual representation of how many batters fitted into each category - to reveal any biases in the underlying data


Feedback
---------------------

* I received feedback from my wife (Laura), who said that that the scatter plot was a bit overwhelming with data, and didn't let them really understand the story that I was trying to tell as the data was very noisy being presented in a single dashboard, which led me to re-think my design choice for the dashboard and how to best present the data
* As a result of this feedback, I wanted to switch to use a tableau story instead of the dashboard to help control the narrative and let the story unfold in a more controlled way
* I made the following changes to help better articulate what I saw in the data and what the core finding was:
 * Add more insights into absolute vs. averages of data
 * Build a narrative through a series of charts, instead of putting all into one
 * Ensure that the flow is clear from board to board

Resources
---------------------

* [Tableau help article](https://onlinehelp.tableau.com/current/pro/desktop/en-us/sortgroup_sets_topn.html) for figuring out how to do a top 10 set
* [Markdown syntax guide](https://daringfireball.net/projects/markdown/basics) - markdown hints to ensure this document is appropriately formatted
* [Markdown renderer](http://markdownlivepreview.com/) - for checking what my final markdown looks like before submitting
