# NBA 2K23 - Exploratory Data Analysis

Data scraped from 2kratings.com - [you check out how I scraped it as well.](https://github.com/gilha/nba-2k23-data-scraper) \
Explored via [Deepnote](https://deepnote.com/workspace/myspace-48fd-0eac2a92-5a71-4337-8f15-180141a776a8/project/nba2k23data-f770f9fc-15a2-479f-b902-8fcc18f53535/notebook/nba2k23_eda-229786d9262e4ee2b959350f970cf925) - it looks much better there (and is somewhat interactive as well!). \

### Some random facts:
- Jazz are the tallest, heaviest, and slowest team in the NBA. It also has the lowest overall rating, making it a strong contender for another title, of the most extreme team.
- Thunder are both 3nd tallest and 2nd leanest out of all 30 teams (looking for that next KD/Giannis/unicorn).
- Bucks, Suns, Celtics are in the top of most success-predicting metrics (and Spurs, Hornets, Pistons, Rockets are at the bottom).
- Warriors are on average the shortest team.
- Mavericks are 27th (3rd lowest) in terms of their average overall rating.
- Grizzlies are the #1 hustle team, by a fairly large margin.
- Bucks, Warriors, Cavaliers are highest IQ team (Spurs, Rockets, Jazz are lowest).
- Lakers, Hornets, Knicks are fastest teams (Jazz, Celtics, Grizzlies the slowest).
- Warriors, Lakers, 76ers are best 3pt shooters (this beautifully reveales the flaw of averages analysis - having a bunch of slightly-above-average shooters such as the case with the Lakers, doesn't translate to high quality 3pt shooting in real life) (Knicks, Hornets, Clippers are the worst on average - again, it's hilarious that the Clippers, a better 3pt shooting team than the Lakers, are ranked at the bottom!)
  - This metric might be skewed by players who aren't really shooting 3s - i.e. having a 25 3pt shooting ratings vs. a 45 3pt shooting ratings both roughly translates to "not a 3pt shooter", but will impact the data differently. 
    - Might be interesting to consider this factor and to try to normalize it, possibly by binning or by scoring differently the skill.
- Suns, Hornets, 76ers are best at drawing fouls (Pacers, Warriors, Celtics are the worst).
- Grizzlies, Kings, Knicks are most hustle (Suns, Spurs, Hornets are least).
- 75% of players are from the United States, 5% from Canada, and the rest is pretty much all-over-the-place
- A non-US player is more likely to be of a big man archetype: taller, heavier, stronger, less explosive, better interior defender but worst perimeter defender, more skillful in the post, less of a playmaker, etc.
  - Further strengthening this observation: 33% and 23% of non-us players are C and PF respectively, where only 13% and 18% from US players.
