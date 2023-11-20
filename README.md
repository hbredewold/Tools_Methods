# Assignment 1
## Harm Bredewold / S4029763

In the following weeks I would like to work on the topic of political leanings on reddit. In my opinion, Reddit is one of the most interesting social media when it comes to politics. While Twitter certainly is a hotbed of political discussion, and is often used by news media to display ‘normal peoples’ political opinions, Reddit is a different place. Reddit has a front-page function, meaning it shows you the most relevant and popular posts at the moment you visit the site. Besides this, Reddit has subreddits, smaller communities mostly around a topic, a band, a game or maybe even a political leaning. It is exactly these subreddits that make Reddit interesting, because it divides the website in different communities, which then can be analyzed, researched and even be compared.

Academia has increasingly been interested in the social media website. One example is the conference paper ‘A Characterization of Political Communities on Reddit’ (Sollman and Hafer, 2019). In their paper, Sollman and Hafer have analyzed a dataset containing 2.6 billion posts from four political subreddits. These four political subreddits have different political leanings, and Sollman and Hafer have compared the subreddits on for example what news source is mostly posted, what are the most popular words in the subreddit and which subreddits have the most bias. The paper shows that Reddit is a fruitful place for political analysis. A more statistical and broader analysis of reddit’s political leaning has been done by Morales et. al. (2021). One of their findings is that: “Reddit has been a tool for political discussion between opposing points of view during the 2016 elections. This behavior is in stark contrast with the echo chamber observed in other polarized debates regarding different topics …” (Morales et. al., 2021, p. 10). 
 
A tool that has been used to analyze reddit forums is called ‘scraping’. According to Adams (2022) scraping has been increasingly used to collect big amounts of textual data from reddit, ranging from comments, to threads and amount of likes. While the paper definitely shows that scraping reddit has become increasingly popular in academics, there are some considerations. Adam underlines that while using Reddit to do research, especially research that involves online users is not per say problematic, researchers have to take caution that they are still using data produced by real people, and should handle the data accordingly. (Adams, 2022, p. 13).

 
This brings us to my research question. Since it has been established that Reddit is a hot bed for political discourse, this will be the aim of my research. The subreddit https://www.reddit.com/r/Politiek is a place where Dutch speaking people can come together and share their opinions on the current political climate in the Netherlands by making submissions or commenting on posts. My research questions is: _Does /r/Politiek have a preferred political party or political leaning?_ With my personal Reddit experience, my hypothesis is that there is one, and I would like to test this hypothesis. 

To test this claim, this research is going to ‘scrape’ the top ‘liked’ posts in the last month (election season in the Netherlands). To give the posts meaning, I am manually going to label the posts a party, since most of the posts are about a specific party of platform. When all the posts are labelled a political party or leaning, I could use python to perform a sentiment analysis on the post to see if the sentiment is mostly negative or mostly positive. When comparing these sentiments to the label that I have manually given the posts, you could make some conclusions about the reception the /r/Politiek community has of the party affiliated posts. There are some downsides though, since maybe some posts are not explicitly about a party, and the fact that smaller parties probably are not represented well in the subreddit. 

The data I would need are the comments I will scrape from the subreddit, which implies that scraping is one of the methods I use. Besides this another method I will use is sentiment analysis, which I will probably do with the NLTK Library in Python. 

## Bibliography:

Morales, De Francisci., Corrado Monti & Michele Starnini. (2021). No echo in the chambers 
of political interactions on Reddit. Sci Rep 11, 2818. https://doi.org/10.1038/s41598-021-81531-x

Nicholas Norman Adams (2022) ‘Scraping’ Reddit posts for academic research? Addressing 
some blurred lines of consent in growing internet-based research trend during the time of Covid-19, International Journal of Social Research Methodology, https://doi.org/10.1080/13645579.2022.2111816 

Soliman, Ahmed & Hafer, Jan & Lemmerich, Florian. (2019). A Characterization of Political 
Communities on Reddit. https://doi.org/10.1145/3342220.3343662 
