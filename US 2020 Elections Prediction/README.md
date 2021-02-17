# US 2020 Elections Prediction

This directory contains the results of an US 2020 Elections Prediction project. 

The project consisted on gathering US tweets, that had a location attribute, containing the names of the candidates and vicepresidents or the name of the political party (Democrats or Republicans)
using a tweet crawler, that uses the python library Tweepy. 

I ran the crawler from the Vicepresidential Debate (October 7th, 2020) to Election Day (November 3rd, 2020) and managed to obtain a database of 550k tweets.  

Then I performed Sentiment Analysis, using vader lexicon, to those tweets and established whether they were for or against the Democrat party. Once I obtained the sentiment of each tweet, 
I grouped them by the user id and computed a predicted vote for that user based on the sentiment of their tweets.

Finally, this information was used to create a Tableau Dashboard that allows to understand the general results. It also allows to understand the results state by state by 
interactively selecting a state.

## Links

The Dashboard can be found in this [link](https://public.tableau.com/views/FinalProjectVisual_16078026360090/US2020ElectionResultsPrediction?:language=es&:display_count=y&publish=yes&:origin=viz_share_link).

The original dataset is not available due to privacy regulations, as it contains the users ID's.

## Dashboard 
