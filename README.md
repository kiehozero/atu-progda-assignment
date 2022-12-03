# Programming for Data Analysis Assignment

A repository for the dataset synthesis project in ATU Programming for Data Analytics 2022

## Task

"For this project you must create a dataset by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish - you might pick on that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python. We suggest you use the `numpy.random` package for this purpose.

Specifically, in this project you should:

1. Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables;

2. Investigate the types of variables involved, their likely distributions, and their relationships with each other;

3. Synthesise/simulate a dataset as closely matching their properties as possible;

4. Detail your research and implement the simulation in a Jupyter notebook - the dataset itself can simply be display in an output cell within the notebook.

Note that this project is about simulation - you must synthesise a dataset. Some students may already have some real-world datasets in their own files. It is okay to base your synthesised dataset on these should you wish (please reference it if you do), but the main task is in this project is to create a synthesised dataset."

## Limitations of Analysis

- lack of declaration information, also ties https://en.wikipedia.org/wiki/Result_(cricket)

## References

Booth, L. (2010) "Turning Points: Covered Pitches". Available at [CricInfo](https://www.espncricinfo.com/story/cricket-s-turning-points-covered-pitches-461172) (Accessed 3rd December, 2022).
\
Kumar, B. (2021) "Matplot lib multiple bar chart". Available at [Python Guides](https://pythonguides.com/matplotlib-multiple-bar-chart/) (Accessed 3rd December, 2022).
\
Leamon, N. and Jones, B. (2021) _Hitting Against the Spin: How Cricket Really Works_. London: Little, Brown Book Group.
\
Marylebone Cricket Club (2022) _The Laws of Cricket_. Available at [MCC](https://www.lords.org/mcc/the-laws-of-cricket/covering-the-pitch) (Accessed 26th November, 2022).
\
NumPy Documentation (2022) "Random Generator". Available at [NumPy.org](https://numpy.org/doc/stable/reference/random/generator.html) (Accessed 15th November, 2022).
\
[Wikipedia](https://en.wikipedia.org/wiki/Probability_distribution#External_links) - change to whichever you use

## Data Queries

[Innings](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=1;opposition=2;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=1;team=2;template=results;tournament_type=2;type=team;view=innings)

[Australian tosses](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=1;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=2;template=results;toss=1;tournament_type=2;type=team;view=innings)

[English tosses](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=2;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=1;template=results;toss=1;tournament_type=2;type=team;view=innings)
