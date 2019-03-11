
## What to expect as an Airbnb Host in Berlin

Airbnb has successfully disrupted the traditional hospitality industry as more and more travelers decide to use Airbnb as their primary accommodation provider. Since its inception in 2008, Airbnb has seen an enormous growth, with the number of rentals listed on its website growing exponentially each year.

In Germany, no city is more popular than Berlin. That implies that Berlin is one of the hottest markets for Airbnb in Europe, with over 22,552 listings as of November 2018. With a size of 891 km², this means there are roughly 25 homes being rented out per km² in Berlin on Airbnb!

Considering the possibility that I might have to relocate for a new data science job, but want to keep my current flat in Berlin (which is quite cheap!), I might wonder if it could be worth it to offer my jewel on Airbnb. Could this perhaps be a profitable option? However, it is difficult for potential hosts to know what the true value of their home is, and how in-demand their home might be. And since location and furniture are obviously fixed for the most part, is there anything else a host can influence - such as description, communication patterns, and/or additional services to boost their earnings?

The following three questions will drive this project:

> **1. Can we determine a fairly spot-on daily price for a new accommodation that fits into its specific market environment and competitors in Berlin?** <br>
> **2. How big is the demand likely to be? What can a host expect with respect to occupancy and earnings here in Berlin? What factors influence how in-demand it is?** <br>
> **3. And lastly: What do visitors like and dislike?**

The first question focuses on the accommodation features and decisions a new host can make with regards to initial presentation, i.e. posting a picture of him- or herself on the website, determining a minimum length of stay, offering instant bookings etc. A machine learning algorithm will be applied to try to get an answer. 
<br> The second question is similar and even stronger. It focuses on geography to explain the demand, but will mainly use visualizations to narrow down the search for answers. 
<br> The last question processes the reviews to find out what peoples' likes and dislikes are. Natural Language Processing (NLP) and specifically Sentiment Analysis are what we will use here.

To not prevent my notebook(s) from ever being read due to their length, I wrote one "paper" - aka notebook - for each question. 

### The datasets

All listings and review data is sourced from the Inside Airbnb website, and was scraped on November 07th 2018.
