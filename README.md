# painting_recommender_for_Met
Recommender system for visitors to use during trips to the Met Art Museum

There are over 2 million pieces of art within The Metropolitan Museum of Art. Navigating through such a large art collection can easily overwhelm any museum goer. Therefore, I’ve created a recommender system which will suggest pieces of art visitors might enjoy. This system will enable visitors to focus on works of art they find attractive. It is a product that enhances the visitor experience. 

This recommender system is easy to use. Once a visitor provides a piece of art s/he enjoys, the recommender will suggest.four other museum pieces s/he may enjoy.

Data from [The Met’s Open Access collection](https://www.metmuseum.org/art/collection/search#!?q=&perPage=20&sortBy=Relevance&sortOrder=asc&offset=0&pageSize=0) was obtained to create the recommendation system. The data collected focus on paintings within the collection since 1900. Upon exploring the data, I decided to create a recommender system built on the premise that painting descriptions can be used to determine similar paintings. In other words, the text associated with each painting is used to build a recommender for the paintings themselves.

----
This repo contains:
 **Code**
 * web scraping.ipynb
 * webscraping2.ipynb
 * classification on blurbs.ipynb
 
 **Data**
 * blurbsComplete.pkl
 * jpg2.pkl
 * sites2.pkl
 
 **Slide Deck**
 ChristineChen_.ppt
 
 
