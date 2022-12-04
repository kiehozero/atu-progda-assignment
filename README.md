# Programming for Data Analysis Assignment

A repository for the dataset synthesis project in ATU Programming for Data Analytics 2022. I have listed here the project requirements given by the lecturer, as well as my referencing and the initial queries I ran. All of my explanations of the dataset are given in the [Jupyter Notebook](assignment.ipynb) that is contained within this repository.

## Task

"For this project you must create a dataset by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish - you might pick on that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python. We suggest you use the `numpy.random` package for this purpose.

Specifically, in this project you should:

1. Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables;

2. Investigate the types of variables involved, their likely distributions, and their relationships with each other;

3. Synthesise/simulate a dataset as closely matching their properties as possible;

4. Detail your research and implement the simulation in a Jupyter notebook - the dataset itself can simply be display in an output cell within the notebook.

Note that this project is about simulation - you must synthesise a dataset. Some students may already have some real-world datasets in their own files. It is okay to base your synthesised dataset on these should you wish (please reference it if you do), but the main task is in this project is to create a synthesised dataset."

## References

Booth, L. (2010) "Turning Points: Covered Pitches". Available at [CricInfo](https://www.espncricinfo.com/story/cricket-s-turning-points-covered-pitches-461172) (Accessed 3rd December, 2022).
\
Datagy.io (2022) "Replace Values in a Pandas Dataframe". Available at [Datagy](https://datagy.io/pandas-replace-values/) (Accessed 4th December, 2022).
\
Ehantharajah, V. (2022) "England feel the funk in bid to overcome unforgiving 'Pindi pitch". Available at [CricInfo](https://www.espncricinfo.com/story/pakistan-vs-england-1st-test-rawalpindi-england-feel-the-funk-in-bid-to-overcome-unforgiving-pindi-pitch-1347874) (Accessed 2nd December, 2022).
\
Geeksforgeeks (2021) "Convert the data type of Pandas column to int." Available at [Geeksforgeeks](https://www.geeksforgeeks.org/convert-the-data-type-of-pandas-column-to-int/) (Accessed 4th December, 2022).
\
Kumar, B. (2021) "Matplot lib multiple bar chart". Available at [Python Guides](https://pythonguides.com/matplotlib-multiple-bar-chart/) (Accessed 3rd December, 2022).
\
Lavalette, T. (2018) "Winning Isn't Everything in Five-Day Cricket, Draws Can Be Rewarding Too." Available at [Forbes](https://www.forbes.com/sites/tristanlavalette/2018/10/13/winning-isnt-everything-in-five-day-cricket-draws-can-be-rewarding-too/?sh=32a7340c71e9) (Accessed 1st December, 2022).
\
Leamon, N. and Jones, B. (2021) _Hitting Against the Spin: How Cricket Really Works_. London: Little, Brown Book Group.
\
Marylebone Cricket Club (2022) _The Laws of Cricket_. Available at [MCC](https://www.lords.org/mcc/the-laws-of-cricket/) (Accessed 26th November, 2022).
\
McGinley, B. (2022) "Time Series". Lecture notebook for the Programming for Data Analysis module, Atlantic Technological University. Available, including my own modification, at [GitHub](https://github.com/kiehozero/atu-progda2022/tree/main/week7-time-series) (Accessed 26th November, 2022).
\
McLoughlin, I. (2022) "Distributions and Generating Random Numbers". Lecture notebook for the Fundamentals of Data Analysis module, Atlantic Technological University. Available, including my own modifications, at [GitHub](https://github.com/kiehozero/atu-fundda2022/tree/main/materials/week5) (Accessed 2nd November, 2022).
\
NumPy Documentation (2022) "Random Generator". Available at [NumPy.org](https://numpy.org/doc/stable/reference/random/generator.html) (Accessed 15th November, 2022).
\
NumPy Documentation (2022) "numpy.random.choice". Available at [NumPy.org](https://numpy.org/doc/stable/reference/random/generated/numpy.random.choice.html) (Accessed 4th December, 2022).
\
NumPy Documentation (2022) "numpy.random.Generator.triangular". Available at [NumPy.org](https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.triangular.html) (Accessed 23rd November, 2022).
\
Pandas Documentation (2022) "pandas.data_range". Available at [Pydata.org](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.date_range.html) (Accessed 4th December, 2022).
\
PyNative (2021) "Python Weighted Random Choices". Available at [PyNative.com](https://pynative.com/python-weighted-random-choices-with-probability/) (Accessed 4th December, 2022).
\
Wikipedia (2022, last edit) "English cricket team in Australia, 1979-80". Available at [Wikipedia](https://en.wikipedia.org/wiki/English_cricket_team_in_Australia_in_1979%E2%80%9380) (Accessed 30th November, 2022).

## Data Queries

[All Innings of Test Matches between England and Australia since 1st January, 1970](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=1;opposition=2;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=1;team=2;template=results;tournament_type=2;type=team;view=innings) (Accessed 20th November, 2022).

[All Innings of Test Matches between England and Australia since 1st January, 1970, in which Australia won the toss](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=1;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=2;template=results;toss=1;tournament_type=2;type=team;view=innings) (Accessed 25th November, 2022).

[All Innings of Test Matches between England and Australia since 1st January, 1970, in which England won the toss](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=1;filter=advanced;host=1;host=2;opposition=2;orderby=start;size=200;spanmin1=1+Jan+1970;spanval1=span;team=1;template=results;toss=1;tournament_type=2;type=team;view=innings) (Accessed 25th November, 2022).

[All Test Matches occurring in 1969](https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?class=1;id=1969;type=year) (Accessed 29th November, 2022).
