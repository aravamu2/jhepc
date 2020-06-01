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

The spread of the COVID-19 and the rise in death toll come as political leaders seek to reopen parts of the country. Given that COVID-19 affects the health and well-being of all residents, local and state officials need information about the extent and impact of COVID-19. Governments increasingly use R0 as a metric for whether the number of cases is growing faster than they can manage or reducing as quickly as they would like. R0 represents the number of new infections estimated to originate from a single case. An R0 below 1 implies the number of cases is reducing, permitting communities to open back up, while an R0 above 1 implies necessitating renewed lockdowns or other measures. The metric describes a snapshot of how the virus is spreading at a given time and place. Therefore, visualizing R0 spatially and temporally is necessary to accurately and effectively report the metric. 

Currently, most COVID-19 visualizations suffer from (1) overplotting, (2) lack of uncertainty component, (3) inability to provide both spatial and temporal context, or (4) inability to compare between different entities at different times.  Thus, geofacetting is an intuitive approach to summarize R0 spatially and temporally for all Wisconsin counties over all time points. It preserves the geographical orientation of the entities and maintains the time dependence of the metric. The method plots multiple variables per entity, namely time-series data of R0 per county to prevent overplotting observed in line plots. It uses more effective visual encoding schemes than just color observed in choropleth maps. Each entity is given equal plot area to help health system officials weigh counties equally and determine geographic hot spots. Hovering over data points provides details-on-demand including the county name, date, number of cases, mean R0, and 95% CI. The semantic mapping of color encodes "risk" where the line and tooltip are red if the number of cases increases fast, yellow if it stays the same or increases slowly, and green if it decreases. Similarly, the plot area encodes "risk" using the current mean R0. The line is the mean R0 and the gray area is the 95% CI or the uncertainty. The horizontal lines denote the boundaries for risk. Also, the user can modify the plots using the zoom, pan, and scale features to a specific view, necessary for reporting.

The interactive at the time of May 30, 2020 shows that there are low-case counts for counties in the north and low- to medium-risk cold-spots in the northeast, northwest, and south to southwest areas of the state. For example, Milwaukee County can be easily identified as high-risk. The R0 is slightly above 1.2 with a decreasing trend. The neighboring counties are also either low- to medium-risk with a low and decreasing trend. Health system officials can decrease hospital resources to meet local needs and divert it to higher risk areas. Currently, multiple health systems including Gundersen Health and Marshfield Clinic use this visualization to anticipate trends and alert health professionals a few critical days in advance. 

word count: 499

Please provide a rendering of the plot in a widely used format. This may be, for example, PDF for print, standalone HTML and Javascript for an interactive plot, or MPEG-4 for a video (max 10Mb). Please verify that you have uploaded the rendering that you intend to submit. *

---

Please provide a link to a public repository (github, gitlab, bitbucket or other service) hosting the code to reproduce the plot either as a Python file, Jupyter notebook, RStudio notebook, or some similar media. If the original data can not be shared for reasons of size or licensing, "fake" data may be substituted, along with an image of the plot using real data. All code required to reproduce the plot must be at this location. *

https://github.com/aravamu2/jhepc

