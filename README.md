# An Analysis of Political Contributions During the 2020 House of Representatives Election

In this part, you will obtain as much data as you can on the campaign contributions received by each candidate. This data is avaiable through the website https://www.opensecrets.org/.
1. Start by scraping the data from the summary page for Tennessee's 7th District, which is available at https://www.opensecrets.org/races/candidates?cycle=2020&id=TN07&spec=N.
    * Make a DataFrame showing, for each candidate:
        * the candidate's name
        * the candidate's party
        * state
        * district number
        * whether the candidate was an incumbent
        * whether the candidate won the race
        * the percentage of the vote that candidate received
        * the total amount raised by that candidate (as a numeric variable)
        * the total amount spent by the candidate (as a numeric variable)
2. Once you have working code for Tennessee's 7th District, expand on your code to capture all of Tennessee's districts.
3. Once you have working code for all of Tennessee's districts, expand on it to capture all states and districts. The number of representatives each state has can be found in a table on this page: https://www.britannica.com/topic/United-States-House-of-Representatives-Seats-by-State-1787120
4. Using your scraped data, investigates different relationships between candidates and the amount of money they raised. Here are some suggestions to get you started, but feel free to pose you own questions or do additional exploration:  
    a. How often does the candidate who raised more money win a race?  
    b. How often does the candidate who spent more money win a race?  
    c. Does the difference between either money raised or money spent seem to influence the likelihood of a candidate winning a race?  
    d. How often does the incumbent candidate win a race?  
    e. Can you detect any relationship between amount of money raised and the incumbent status of a candidate?

### Bonus Questions:
If you complete all of the above, you can attempt these challenging bonus questions.

Open Secrets also gives a detailed breakdown of contributions by source.

Scrape these pages to get information on contributions by source. See if you can find anything interesting in terms of the source of contributions. Some examples to get you started:
* What does the overall distribution of funding sources look like?
* Is there any detectable difference in contribution sources between Democrat and Republican candidates?
* Do the funding sources for either the winning candidate or incumbent candidate differ from the other candidates?