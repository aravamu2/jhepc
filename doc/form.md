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

The continued spread of the COVID-19 outbreak in the United States, and the continued rise in the death toll, comes as political leaders seek to reopen parts of the country. Given that COVID-19 affects the health and well-being of all residents in the United States, local and state officials need information about the extent and impact of COVID-19 to make decisions. Governments increasingly use R0 as a metric for whether the number of COVID-19 cases are growing faster than they can manage or reducing as quickly as they would like. R0 represents the number of new infections estimated to originate from a single case. An R0 below 1 implies that the number of cases is reducing permitting communities to open back up. An R0 above 1 indicates that the number of cases is growing necessitating renewed lockdowns or other measures. There is no such thing as a fixed R0, where the metric is used to describe a snapshot of how the virus is reproducing in a given time and place. Therefore, visualizing R0 spatially and temporally is necessary to accurately and effectively report the metric. 

Currently, most COVID-19 visualizations suffer from (1) overplotting, (2) lack of uncertainty component, (3) inability to provide both spatial and temporal context separately, or (4) inability to compare between different entities at different times simultaneously.  Therefore, the geofacetted visualization is an intuitive approach to summarize R0 spatially and temporally for all Wisconsin counties and overall timepoints. It strives to preserve the original geographical orientation of the entities and maintains the time dependence of the metric. Moreover, the method plots multiple variables or values per geographic entity, namely timeseries data of R0 per county to prevent overplotting in the case of line plots. Furthermore, the process use more effective visual encoding schemes than just color in the case of choropleth maps. Additionally, each geographic entity is given the equal plot area for health system officials to weight counties equally and determine geographic hot spots. Hovering over any data point provides details-on-demand including the county name, date, number of cases, posterior mean (Mean R0), and 95% credible interval (2.5 Percentile and 97.5 Percentile). The semantic mapping of color is used to encode "risk" where the plot, line, and tooltip are red if the number of cases increases relatively fast, yellow if it stays the same or increases relatively slow, and green if it decreases. The line is the posterior mean representing the estimate and the gray area is the 95% credible interval representing the uncertainty of the estimate. The horizontal lines provide the boundary conditions for the risk domains. Lastly, the user can modify the plots using the zoom, pan, and scale features to a specific view, necessary for governmental reporting.

The interactive visualization at the time of May 30, 2020 shows that there are low-case counts for counties in the north and low- to medium-risk cold-spots in the northeast, northwest and south to south west areas of the state. Given the geographical context, Milwaukee County can be easily identified as a high-risk county. However, note the R0 slightly above 1.2 using the tool tip and decreasing trend of R0 by the plot where the neighboring counties are also either low- to medium-risk or present a relatively low and decreasing trend of R0 as well. Therefore, health system officials can infer a decrease in hospital resources to meet local needs such that it can be diverted higher risk areas of the state to meet more pressing needs. Currently, multiple health systems including Gundersen Health and Marshfield Clinic use the visualization to anticipate trends and alert health professionals a few critical days in advance.

word count: 606

Please provide a rendering of the plot in a widely used format. This may be, for example, PDF for print, standalone HTML and Javascript for an interactive plot, or MPEG-4 for a video (max 10Mb). Please verify that you have uploaded the rendering that you intend to submit. *

---

Please provide a link to a public repository (github, gitlab, bitbucket or other service) hosting the code to reproduce the plot either as a Python file, Jupyter notebook, RStudio notebook, or some similar media. If the original data can not be shared for reasons of size or licensing, "fake" data may be substituted, along with an image of the plot using real data. All code required to reproduce the plot must be at this location. *

https://github.com/aravamu2/jhepc

