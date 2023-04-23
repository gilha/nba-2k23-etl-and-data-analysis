# NBA 2K23 - ETL + Exploratory Data Analysis

* [Data scraped](https://github.com/gilha/nba-2k23-etl-and-data-analysis/blob/main/nba2k23_ETL_scraping.ipynb) from 2kratings.com
* Explored using [Deepnote - it looks much better there!](https://deepnote.com/workspace/myspace-48fd-0eac2a92-5a71-4337-8f15-180141a776a8/project/nba2k23data-f770f9fc-15a2-479f-b902-8fcc18f53535/notebook/nba2k23_exploratory_data_analysis-229786d9262e4ee2b959350f970cf925)
* Using `SQL`, `Python` (`pandas`, `re`, `BeautifulSoup`, `selenium`).

### Some random facts:
- Jazz are the tallest, heaviest, and slowest team in the NBA. It also has the lowest overall rating.
- Thunder are both 3nd tallest and 2nd leanest out of all 30 teams (i.e. looking for that next KD/Giannis/unicorn).
- Warriors are on average the shortest team.
- Grizzlies are the #1 hustle team, by a fairly large margin.
- Mavericks are 27th (4rd lowest) in terms of their average overall rating. [update April 23 - no wonder they did not make it to the playoff!]

- Bucks, Suns, Celtics are in the top of most success-predicting metrics (and Spurs, Hornets, Pistons, Rockets are at the bottom).
- Bucks, Warriors, Cavaliers are highest IQ team (Spurs, Rockets, Jazz are lowest).

- Warriors, Lakers, 76ers are best 3pt shooters (this beautifully reveales the flaw of averages analysis - having a bunch of slightly-above-average shooters such as the case with the Lakers, doesn't translate to high quality 3pt shooting in real life) (Knicks, Hornets, Clippers are the worst on average - again, it's hilarious that the Clippers, a better 3pt shooting team than the Lakers, are ranked at the bottom!)
  - This metric might be skewed by players who aren't really shooting 3s - i.e. having a 25 3pt shooting ratings vs. a 45 3pt shooting ratings both roughly translates to "not a 3pt shooter", but will impact the data differently. 

- 75% of players are from the United States, 5% from Canada, and the rest is pretty much all-over-the-place
- A non-US player is more likely to be of a big man archetype: taller, heavier, stronger, less explosive, better interior defender but worst perimeter defender, more skillful in the post, less of a playmaker, etc. (33% of non-us players are primarily Centers, while only 13% of US players are Centers).


-  The average NBA player is 200cm tall (about 6'6"), a mediocre shooter from all ranges, and generally doesn't really possess qualities which are associated with traditional big men (e.g. strength, playing in the post, interior defense, etc.). A further verification of this observation is that when we test which NBA players are the furthest away from average - centers dominate the list:
-  ![least avg nba player 2k23](https://user-images.githubusercontent.com/18117093/220134122-f35cf5ce-4863-49b6-9f35-31ab2a536ed8.png)
-  ### And the most average NBA players are...:
-  ![most avg nba players 2k2023](https://user-images.githubusercontent.com/18117093/220134252-38db22a6-e303-4cc5-8c42-6280fdd95f33.png)
  -  (Yes, the Polish dude that shoots one-handed fts is the most average of 'em all.)
-  ## We can also be a bit more sophisticated than that, and test how the average player looks like for each position!
-  ### Starting with the most average PGs:
-  ![most avg pg](https://user-images.githubusercontent.com/18117093/220134902-7fbd8e45-4ced-4944-8f3c-c02325d87c5e.png)
  -  Killian Hayes is average? That's awesome!
  -  Jamal Murray is average? I always knew something was fishy about that dude. [April 2023 update - he's sneakily good, and most likely underrated]
-  ### Least average PGs:
- ![least avg pg](https://user-images.githubusercontent.com/18117093/220135346-cdd8a5e6-f4f7-4bf7-8e4d-da6476cddb84.png)
  - A mix of uniquely talented and of fringely weird players (Ben, I'm looking at you).
- ### Most average SGs:
- ![most avg sg](https://user-images.githubusercontent.com/18117093/220136154-8b015377-8fd6-4440-ba7c-c5c56efd8f78.png)
- ### Least average SGs:
- ![least avg sg](https://user-images.githubusercontent.com/18117093/220136388-e5056e08-80cf-4e05-8729-7da4380bd469.png)
- ### Most average SFs:
- ![most avg sf](https://user-images.githubusercontent.com/18117093/220136721-08297e6b-399e-4979-9ae4-65e92b4d9910.png)
  - It all just resonates, to be honest.
- ### Least average SFs:
- ![least avg sf](https://user-images.githubusercontent.com/18117093/220136956-329d0790-3d5d-4ae0-8469-f1b9bf6f5f35.png)
- ### Most average PFs:
- ![most avg pf](https://user-images.githubusercontent.com/18117093/220137246-ff59ed6c-26d9-457d-9239-df63fefb3f34.png)
  - Sochan got mogged.
- ### Least average PFs:
- ![least avg pf](https://user-images.githubusercontent.com/18117093/220137533-412c99ae-a6a1-4021-8028-1b4fb137be88.png)
- ### Most average Cs:
- ![most avg c](https://user-images.githubusercontent.com/18117093/220137698-7063887a-d49d-407a-8f21-fbe4350452cf.png)
  - Wiseman is average? That's awesome!
- ### Least average Cs:
- ![least avg c](https://user-images.githubusercontent.com/18117093/220138008-2f64014c-1842-419c-8449-7ea660507c04.png)



- ### Players with the least game IQ:
-  ![lowest iq nba2k23](https://user-images.githubusercontent.com/18117093/220132328-6692b613-a6f6-40e5-a34d-1b40a4751aa5.png)





