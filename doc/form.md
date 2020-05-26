2020 - John Hunter Excellence in Plotting contest

In memory of John Hunter, we are pleased to announce the SciPy John Hunter Excellence in Plotting Competition for 2020. This open competition aims to highlight the importance of data visualization to scientific progress and showcase the capabilities of open source software.

Entries may take the definition of "visualization" rather broadly. Entries may be, for example, a traditional printed plot, an interactive visualization for the web, a dashboard, or an animation.

Winners will be announced at SciPy 2020 in Austin, TX but participants do not need to attend the SciPy conference.

Questions about the contest may be submitted to jhepc.organizers@gmail.com 

Entries must be submitted by June, 1st, 2020
The name and photo associated with your Google account will be recorded when you upload files and submit this form. Not aravamu2@gmail.com? Switch account
* Required

Email address *

aravamuthan@wisc.edu, spkent@wisc.edu

Author names *

Srikanth Aravamuthan, Sean Kent

Figure title *

Spatial panels for temporal instantaneous R0 data geofaceted by Wisconsin counties.

Abstract: Description of the figure and its importance for a general scientific audience. Please discuss the information the visualization is intended to communicate and how the visualization achieves this task. (300 - 500 words) *

The COVID-19 outbreak in the United States, which now has the highest number of known cases in the world, has exploded over the last three months. In recent weeks, more than 20,000 new cases have been announced across the United States each day, keeping the country on a stubborn plateau instead of the sharp downward curve scientists had hoped for. The continued spread of the virus, and the continued rise in the death toll, comes as political leaders seek to reopen parts of the country. Given that COVID-19 affects the health and well-being of all residents in the United States, local and state officials need information about the extent and impact of COVID-19 to make decisions. Focusing on Wisconsin counties offer an opportunity to search directly for trends that would be relevant to Wisconsin health officials, health system leaders, and other interested parties. 

Governments increasingly use R0 as a metric for whether the number of COVID-19 cases are growing faster than they can manage or reducing as quickly as they would like. R0 represents the number of new infections estimated to originate from a single case. For example, if R0 is 2.5, then one person with COVID-19 is expected to infect, on average, 2.5 others. An R0 below 1 implies that the number of cases is reducing permitting communities to open back up. An R0 above 1 indicates that the number of cases is growing necessitating renewed lockdowns or other measures. 

There is no such thing as a fixed R0, where the metric is used to describe a snapshot of how the virus is reproducing in a given time and place. Therefore, visualizing R0 by both spatially and temporally is necessary to accurately and effectively report the metric. Moreover, the main issue for visualizing R0 is plotting the estimate and the uncertainty of the estimate individually to prevent overplotting and organizing the plots to provide greater context and compare between different counties and timepoints simultaneously. 

Geofaceting a series of line plots for Wisconsin counties into a grid would strives to preserve some of the original geographical orientation of the entities and maintain the time dependence of the metric. Hovering over any data point provides details-on-demand including the county name, date, number of cases, posterior mean (Mean R0), and 95% credible interval (2.5 Percentile and 97.5 Percentile). This gives context to the visualization and allows a user to dig deep into the data that they care about. The color encodes the "risk" where the plot is red if the number of cases increases relatively fast, yellow if the number of cases stays the same or increases relatively slow, and green if the number of cases decreases. The line is the posterior mean representing the estimate and the gray area is the 95% credible interval representing the uncertainty of the estimate. 

Thus, the interactive visualization communicates how contagious COVID-19 is for a given county at a specific time. Furthermore, it displays the overall trend of the virus for a given county and the spatial clustering of the virus at the current time. The user can instantaneously identify "high-risk" areas in the plot and further examine the direction in the specific panel. Additionally, the user can also compare between different counties at different timepoints where it would be difficult to do so using Simple plot or animation. The interactive has a lot of advantages for those deciding where to focus interventions. Currently, multiple health systems including Gundersen Health and Marshfield Clinic use the visualization to anticipate trends and alert health professionals a few critical days in advance.




Please provide a rendering of the plot in a widely used format. This may be, for example, PDF for print, standalone HTML and Javascript for an interactive plot, or MPEG-4 for a video (max 10Mb). Please verify that you have uploaded the rendering that you intend to submit. *

---

Please provide a link to a public repository (github, gitlab, bitbucket or other service) hosting the code to reproduce the plot either as a Python file, Jupyter notebook, RStudio notebook, or some similar media. If the original data can not be shared for reasons of size or licensing, "fake" data may be substituted, along with an image of the plot using real data. All code required to reproduce the plot must be at this location. *

https://github.com/aravamu2/jhepc

