# MICROSOFT-STUDIO-PROJECT
# INTRODUCTION
Microsoft is a multinational technology company that was founded on April 4, 1975, by Bill Gates and Paul Allen. It is one of the world's largest and most influential technology corporations. Headquartered in Redmond, Washington, USA.

The company's primary focus is on developing, manufacturing, licensing, and supporting software products and services. Microsoft is best known for its operating system, Microsoft Windows, which is used by a vast majority of personal computers worldwide.

Microsoft, witnessing the success of major companies producing original video content, seeks to venture into the movie industry by establishing a new movie studio. However, lacking experience in film production, they have entrusted us with the task of exploring the most successful film types at the box office. Our mission is to delve into the datasets from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers to extract essential insights. These findings will serve as actionable recommendations for the head of Microsoft's new movie studio, aiding them in deciding which types of films to create for maximum impact and commercial success.

# OBJECTIVES

1. Understand the film industry
2. Explore genre ratings, popularity and runtime
3. Analyse the profitability of the production of sequels
4. Select seasoned crew members per genre

# Understand the film industry

TOP TEN STUDIOS WITH THE LARGEST MARKETSHARE (REVENUE)

![MARKETSHARE REVENUE](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/338bd96a-3f36-4ebf-8f6b-26722cd09f09)

Observation:
1. BV (Buena Vista by Disney): Total Revenue - $44.25 billion, Percentage Market Share - 16.10%
2. Fox: Total Revenue - $31.04 billion, Percentage Market Share - 11.30%
3. WB (Warner Bros): Total Revenue - $31.03 billion, Percentage Market Share - 11.29%
4. Uni. (Universal Studios): Total Revenue - $29.82 billion, Percentage Market Share - 10.85%
5. Sony: Total Revenue - $22.48 billion, Percentage Market Share - 8.18%
6. Par. (Paramount Pictures): Total Revenue - $19.69 billion, Percentage Market Share - 7.16%

TOP TEN STUDIOS WITH THE LARGEST MARKETSHARE (MOVIE PRODUCTION)

![market share 2](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/697bd60d-6b6d-443b-96b4-df62744bc4cd)

Observation:
1. Universal (Uni.): Number of Movies: 147, Total Revenue: $29.81536 billion
2. Warner Bros. (WB): Number of Movies: 140, Total Revenue: $31.02995 billion
3. 20th Century Fox (Fox): Number of Movies: 136, Total Revenue: $31.04417 billion
4. Sony Pictures (Sony): Number of Movies: 109, Total Revenue: $22.48252 billion
5. Buena Vista (BV): Number of Movies: 106, Total Revenue: $44.25168 billion
6. Lionsgate Films (LGF): Number of Movies: 102, Total Revenue: $8.885583 billion
 
VISUALIZE THE DIFFERENCES IN MARKETSHARES

![TOP10STUDIOS](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/108aa875-40fe-4310-b856-d1cb48113c46)


Observation:
* Most studios appear in both charts, but it's important to note that despite IFC having the highest movie production, they don't appear in the top 10 studios for total revenue. On the other hand, BV holds a 16% market share in revenue but ranks 7th in the number of movies produced.
* WB(NL), LG/S, and P/DW are among the top ten movies in terms of revenue but are not in the top ten studios for the number of movies generated.
* Conversely, SPC, Magn., and IFC are among the top ten movie studios in terms of movie production, but they don't appear in the top ten in terms of market share for revenue.

This is an indication that a studio does not really have to generate more movies to have more revenue.

Inasmuch as a higher production of movies yields to higher revenue, blindly increasing movie production is not necessarily a guaranteed strategy for generating higher revenue. Factors such as film quality, marketing efforts, audience preferences, and competition within the industry also play crucial roles in determining revenue.

RELATIONSHIP BETWEEN THE NUMBER OF MOVIES  PRODUCED AND TOTAL REVENUE

![CORRELATION](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/f058cd87-c0be-4dfb-8c3e-3cc2bf694bb8)

Observation:
* In this analysis, we observe that the majority of studios that released fewer than 100 movies have achieved total revenues of less than 10 billion dollars. 
* Only four studios that produced more than 100 movies managed to stay below the 10 billion dollars mark. 
On the other hand, it is noteworthy that only six studios, out of those that produced more than 100 movies, achieved significantly greater revenue than 10 billion dollars.


# Explore genre ratings, popularity and runtime

TOP-RATED GENRES (TOP-TEN)

![RATINGS](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/7dcf5ed3-b1c3-41f6-b0ac-f0d630fc99b1)

Observation:
* Besides the usual action, drama, comedy and thriller genres gannering high ratings over the years. There is unusual 'less fun' genres that have high ratings.
* Documentaries, Reality TV, Biography, History and News genres have one thing in common: they tell the personal stories of individuals, highlighting their struggles, triumphs, and contributions. 

These human stories can evoke strong emotions and create a powerful connection with viewers, leading to higher ratings.

AVERAGE RUNTIME OF TOP RATED GENRES (TOP -TEN)

![RUNTIME](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/d7bb3cdd-3a40-4207-b0cb-b3ac4997c5a5)

Observation:
* These values represent the average runtime for each top performing genre combination, providing insights into the typical length of movies or TV shows within each genre with the highest ratings. 
* For example, Game-Show has the longest average runtime (130 minutes), while Drama, Short has the shortest average runtime (18 minutes). 

Microsoft now understands audience preferences and expectations with regard to runtime in different high-rated genres.

POPULARITY OF TOP TEN GENRES BY AVERAGE NUMBER OF VOTES

![NUMBER OF VOTES](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/6717c864-4a49-40ef-a875-889975aa839e)

Observation:
* We can see that the genre combination "Mystery, News, Thriller" has the highest average number of votes, indicating that it is the most popular genre combination among the top 10. 
* On the other hand, genres like "Comedy, Documentary, Fantasy" and "Biography, History, Music" have lower average numbers of votes, suggesting they might be less popular among viewers.

It's important to note that the number of votes is an indication of a movie's popularity and audience engagement. However, the sample size for each genre combination may vary, which can affect the average number of votes.

RELATIONSHIP BETWEEN MOVIE RATINGS, RUNTIME AND NUMBER OF VOTES

![HEAT MAP](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/f94f1232-01cb-429c-85fe-c843a9784e2a)

Observation:
* This heatmap indicates that movie ratings are not influenced by the length of the movie (runtime) of popularity (number of votes).
* These weak relationships suggest that factors beyond the ones considered may have a more substantial influence on the success and popularity of these highly-rated films.



# Analyse the profitability of the production of sequels

PROFITABILITY OF PRODUCTION OF SEQUELS

![LINEGRAPH](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/0e166da4-4968-482d-badb-faa1eb4966d5)

Observation:
* On average, the sequels performed better with regard to increase profits from their original films making it profitable to produce sequels.
* On the other hand, there is a cost implication with the increase in production budget to realise this added profit in releasing sequels.
* Not all sequels had an increase in profits. Some sequels performed worse than the original films.

It is still a profitable venture since the sequels had an overall profit, only that some got less profit than the original film.

RELATIONSHIP BETWEEN CHANGES IN BUDGET AND PROFIT IN SEQUELS

![SEQUELS](https://github.com/jennifernjeri/MICROSOFT-STUDIO-PROJECT/assets/25104993/5139a2c2-702f-44ad-bcf8-975fab70f0ee)

Observation:
* There is a general positive trend. As the budget difference increases, there is a tendency for the gross profit to increase as well. This indicates that movies with larger budget increase tend to have greater profit/loss differences between their earliest and latest releases.
* Some data points deviate from the general trend and are located far from the main cluster. These are outliers that represent sequels with unusual budget and profit changes compared to the majority of the dataset.

Other factors besides budget changes may also influence the resulting profit changes.

# Select seasoned crew members per genre

* Choosing the appropriate crew tailored to each genre will provide Microsoft with a valuable headstart in the movie industry. 
* To aid in this process, I have attached a containing a comprehensive list of writers and directors per respective genres (DIRECTORS AND WRITERS PER GENRE.pdf). 

By leveraging this valuable resource, Microsoft can align its productions with skilled professionals who excel in delivering captivating narratives for each specific genre, setting the stage for a successful foray into the world of filmmaking.

# RECOMMENDATIONS
1. Adopt Strategies from Top Movie Studios: Microsoft can learn from successful movie studios by implementing their marketing and production strategies. Studying and emulating the approaches that have proven effective in the industry can give Microsoft a competitive edge.
2. Focus on Popular Genres: To ensure a successful entry into the movie industry, Microsoft should concentrate their initial movie production on popular genres. By catering to well-established audience preferences, they can increase the chances of attracting a broader viewership.
3. Emphasize Movie Quality over Budget: High movie budgets do not guarantee higher returns. Instead, Microsoft should prioritize qualitative aspects of movie-making, such as compelling storytelling, well-crafted scripts, and collaborating with experienced directors. This focus on quality can lead to better reception from audiences and critics alike.
4. Collaboration: Microsoft's collaboration with seasoned directors and writers can set the stage for cinematic triumphs.

By following these recommendations, Microsoft can overcome the barriers to entry in the movie industry and establish a strong presence in this new domain, leveraging its technological expertise while delivering high-quality films that resonate with audiences.

