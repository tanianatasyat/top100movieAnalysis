**PROJECT 1**

I want you to do a data analysis on the data. What do you think is interesting about this data? Tell a story within 2 pages (excluding figures) about some interesting thing you have discovered by looking at the data.
For example, you might consider whether the director has an impact on movie box office revenue, or whether some directors only focus on making certain type of moves. Another thing you might consider is whether there is a relationship between the box office revenue and the user’s ratings on the movie.
The assignment code that runs on its own (Web crawling + Data analysis) should be handed in using a Jupter Notebook file. (Project Credit: Wang, 2021)

**Analysis Summary**
- 70% of the top 10 movies are released before 2000. It showed that Generation-Z does not like to rate a movie in a website.
<img width="765" alt="Screen Shot 2022-03-18 at 12 03 35" src="https://user-images.githubusercontent.com/78801155/158940795-44db1a85-254d-4e3c-997d-a573fc10ba0c.png">
<img width="303" alt="Screen Shot 2022-03-18 at 12 04 03" src="https://user-images.githubusercontent.com/78801155/158940835-efdf6eab-fd98-4f46-9239-4c21c67bdf4b.png">

- Rating does not guarantee the movies revenue. People rather care about the content of the movies itself, if they like it then they will buy the ticket to watch the movie.
<img width="604" alt="Screen Shot 2022-03-18 at 12 04 39" src="https://user-images.githubusercontent.com/78801155/158940890-d043e956-cc80-451e-8a08-f8131fcbeb79.png">

- Duration does not affect the movies rating.
<img width="626" alt="Screen Shot 2022-03-18 at 12 09 11" src="https://user-images.githubusercontent.com/78801155/158941279-bd79b3c0-1286-40f1-8c5a-665031ddb293.png">

-  

**REPORT**
# Top 100 Movies from IMDB Analysis: Does the IMDB rating reliable?
In recent years, box office movies have gotten more attention from the public. Mcclintock (2021) predicts that the revenues of the global box office movies in 2021 will be 80% ahead of 2020 but still 49% behind 2019. Therefore, it is essential to analyse all-time favourite movies to give viewers insight into what is measured as a good movie. The top 100 movies from Internet Movie Database (IMDB) have been scraped into a single CSV file using BeautifulSoup as the Python library to make this analysis. Below is provided the analysis result for the top movies based on the IMDB users' preference.

1. All-time favourite movies based on IMDB: The top 10 movies

According to the IMDB website, "The Shawshank Redemption" movie released in 1994 has the highest rating in IMDB, 9.3, with nearly 2.5 million people votes. In fact, 1994 is also the mode and median for the all-time favourite movies, which means films in 1994 are mostly liked by the viewers. For instance, there are five titles mentioned in the list produced in 1994, and 2 of those movies are in the top 10 ratings (Table 1). Cykiert (2014) also argued that 1994 was the best year for the film industry. In addition, from the first top ten movies, only three movies were produced after 2000 but before 2010 (Table 1). The old movies are preferred rather than the new movies. In addition, drama is considered as the best genre for a movie. 90% of the movies in the top 10 list were categorized as a drama, and people also like the combination of drama and crime genre in a movie.

1.1. All-time favourite movies based on IMDB: The old movies VS the new movies

Furthermore, the range of movies' release years is 89 years, from 1931 to 2020. Interestingly, 65 movies were produced before 2000, whereas only 35 were produced after 2000 (Figure 1). Do those old movies still good enough and worth watching now? One of the reasons movies before 2000 still successfully hit the top 100 list is that the old movies receive more reviews than the new movies (Bischoff, 2016). It is possible that since the IMDB started its service in the 1990s and within a few years, this site became popular, and it affected the movies review (Bischoff, 2016). Nevertheless, reviewing a film in IMDB is quite rare activity nowadays, especially for Generation Z. That is why new movies have less rating rather than the old movies.

2. Revenue: What factors do affect the movie's revenue?

Based on the analysis, movies that were produced in 2019 had the highest revenue, accounting for a total of 1247.19 million USD, while the average is 415.7 million USD (Figure 2). In that year, one of the Avengers sequels, Endgame, reached the highest cumulative income, 858 million USD (Table 2). In addition, another Avengers sequel, Infinite War, produced in 2018, also placed in a second position with more than 678 million US dollars. If we analyze it further, it is interesting that most of the movies in the highest revenue position mostly are the continuation, such as Avengers, The Dark Knight, The Lord of the Rings, and Star Wars. In other words, the success of these movies might depend on the content, which is the director and the actors that they were known before. For instance, the Avengers and the Star Wars' main casts remain the same for their sequel. On the contrary, Christopher Nolan has directed six movies chosen as the all-time best movie. Also, Tom Hanks played 4 times in the top 100 movies, which is the most compared to other actors in the top 100 movies. Although they did not contribute to the sequel movies, they still successfully hit the top 100. However, the mean rating from 2019 shows no relationship between rating with either income or votes (Figure 3 and 4).

3. Duration: Does the movie's runtime affect the rating of the movie?

Dahlgreen (2015) stated that the ideal duration for a movie is between 90 to 120 minutes. However, the mean duration of the all-time favorite movies is 134.62 minutes or approximately equal to 2 hours and 15 minutes (Figure 5). In fact, more than half of the movies exceed the ideal time and even the average time (Figure 6). The longest duration in the 100 best movies is "Once Upon a Time in America" at 229 minutes, while the shortest is "Toy Story" at 81 minutes. Rosser (2019) reported that duration does not affect the movie's revenue and rating. In the report, he took "Avengers: Endgame" from 2019 as an example. It ran for 181 minutes yet still reached a high rating and cumulative income.

In conclusion, people do not care about the rating and the duration of a movie, but they are more considerate about the director and the actors, which is the content they have recognized before. It is proven from the top movies' revenue list, mostly it has the same directors and actors. When the revenue is high, it means more people had spent their money to watch the movie that they consider worth watching. Jasper (2018) mentioned that we could use the movie review website as a reference, but we cannot fully believe in IMDB reviews since they are biased towards men's preferences (Reynolds, 2017). Therefore, IMDB rating is not reliable for people to judge whether it is a good movie or not.
