---
title: ""

categories:
  - Projects
tags:
  - Projects
  - osu!

permalink: /osu-rank-one/
---

# History of osu! Rank 1

*A project to create the definative timeline of players who had reached rank 1 in osu!*

---

During the first half of 2021, I led a project to create the definitive timeline of players who had reached rank 1 on the global ranking leaderboard in the video game osu!, using historical data to model day-by-day leaderboards. This project was started out of frustration with existing lists on the internet being inconsistent and having incorrect data. While the last decade has been well documented, the period stretching back to 2007 varies in its levels of quality. Our solution to this was to create an estimated reconstruction of the Ranked Score global leaderboard.

We first gathered all public records of the ranked score leaderboards and collated them into a list of sources. Then, we reached out to players from that time period to see if they held any pieces of information from that time period that we could date back to a specific point in time. Once we had a list of suspected players who had reached rank 1, we started the process of gathering every score that is available through the osu! API and creating a timeline of their ranked score over time. Using our sources, we could calculate the difference in score between what our sources tell us and the score data that is available to us. Then, on the days that we are missing data, we can interpolate our missing score using the number of scores submitted on each day to create an estimation of how much score a player had on a defined day where no sources are available. This allows us to closely identify the days where the leaderboard would change, as not every change in rank 1 was archived. The result of this was creating new insights into the various reigns while proving which information is and isn't hearsay.

My role in this was as project lead. Most of my efforts were in gathering and processing sources, writing scripts, and gathering data from the osu! API, as well as creating our estimated reconstructed leaderboard and writing the corresponding wiki article.

## Documents
[<i class="fa fa-table"></i> View Research Documents](https://drive.google.com/drive/folders/10h2T5AT8XOpEPfb087CiFCs1amv9842t?usp=drive_link){: .btn .btn--primary .btn--large}.

[<i class="fa fa-table"></i> View Wiki Page](https://osu.ppy.sh/wiki/en/History_of_osu%21/Online_rankings/osu%21){: .btn .btn--primary .btn--large}

![estimated reconstruction of the Ranked Score global leaderboard](/assets/images/osurankonegraph.png)