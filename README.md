# UTT-DataBC-Project-1

 Summarize where and how you found the data you used to answer these questions
	All Data was found using the https://quickstats.nass.usda.gov/ API. The data provided only includes numbers of honey producing colonies for operations with five or more colonies.
 Describe the data exploration and cleanup process (accompanied by your Jupyter Notebook)
	While the data was given to us in a csv format that we could have downloaded. We instead built an API to collect and parse through the data. There were numerous issues in generating the correct syntax but eventually we became quite competent in the USDA API.
	Different things to account for during datacleanup was values coming over as objects, removal of , or . and then converting to strings.
	Dealing with different date/time issues, specifically working with quarters and years and generating a meaningful graph.
 Describe the analysis process (accompanied by your Jupyter Notebook)
	The colonoy process has the ability to generate a graph for each state as well as the US Total, this allowed us to see multiple trends of decreasing colony counts during the 90s-00s and colony recovery during the 10s.
	While parsing through the data we were able to determine that Varroa Mites(INSERT SCARY PICTURE) were a main pest that affected bee colonies. If we had more time I would be interested in diving deeper into how the Bee colonies were directly affected by Varroa Mites.
 Summarize your conclusions. This should include a numerical summary (i.e., what data did your analysis yield), as well as visualizations of that summary (plots of the final analysis data)
	Bee colonies were hit heavily during the 90s and 00s and have since started to recover. This damage can be attributed to many different factors presented by my partners.