Finalize one Capstone idea based on the feedback you got from mentor(s) and peers on your Section 1 submission, and also based on your newly acquired understanding of the tools and data wrangling. Submit a project proposal - a short (1-2 page) document that answers the following questions:
- What is the problem you want to solve?

Big cities typically consist of a number of neighborhoods with distinct qualities. One neighborhood may be more upscale, the other may be more urban, crime may be higher in a certain neighborhood, traffic may be a big problem in another, etc. People living in the city usually know about the neighborhoods, but this "insider" knowledge is not as easily accessible unless you know someone from the city -- looking up the Wikipedia article of the city won't be of much help. Searching sites like reddit.com or asking on a forum may be your only options if you need to access this information online. But even then, it is likely to get mixed messages which can be frustrating. 
- Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?

The typical client would be someone who is about to relocate to a new city. If this person has never been to this city, and wants to rent a place, he/she will be very interested in what each neighborhood has to offer. My analysis could give this person an idea about what could be a suitable place for him/her to rent their first apartment. In addition, the person can learn other valuable information about, e.g., what the better neighborhoods are for social life. Overall, the clients will have a better sense about the city they are about to move to. This also helps with the anxiety that comes with this big change in their life.
- What data are you going to use for this? How will you acquire this data?

I will use text reviews made available by yelp for their "Yelp Dataset Challenge". The dataset includes almost 1.6 million reviews on local businesses from ten cities. 
- In brief, outline your approach to solving this problem (knowing that this might change later).

Each local business in the yelp data comes tagged with location. So, it is possible to group businesses (hence, their respective reviews) by location. I will apply Topic Modeling to the review text to extract themes common in each neighborhood. Dominant topics coming out of reviews for a neighborhood's business can provide clues to the overall qualities of that neighborhood.
- What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

I will make available the Python code and prepare a slide deck and a paper that present my findings. I may also publish a blog post.

