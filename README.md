# Mod 1 Project: Microsoft RFP
Danny Mocombe, Joey Billet, Tom Hill

# Project:

Microsoft has submitted an RFP to pho[0]ton - a data driven consulting agency - that has asked the following:

Microsoft would like to get into the film industry and would like to know which approach makes the most sense.

After initial diligence within the team, we came up with the following questions:

1. How should Microsoft enter the market?
2. What kind of content should they make?
3. What does the industry look like right now?
4. What combination of variables will produce the right kind of return?

# Approach:

In order to get to an actionable insight, we performed the following steps:

*  Our partners at the Flatiron School provided an initial data set from IDMB that we first cleaned up with Pandas
*  We then made two API calls via Requests to TMDB (The Film Database) to obtain a consistent set of data based on IDMB ID's.
*  The API response data included budget, revenue, and MPAA rating - three very important variables for our project
*  We then took all of our data, combined it, and cleanded it to produce a sample size of around 1800 movies 
*  Then using Matplotlib and Seaborn, we created visualizations to support our data findings

# Technical Documentation can be found in the following notebooks:

* DATA_CLEANING
* TMDB_API_CALLS
* VISUALIZATIONS 

# Presentation:

