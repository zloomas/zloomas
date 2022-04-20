## Greetings :wave:

Hi, I'm Zach!

### About me :nerd_face:
- Florida Man :palm_tree: currently in Virginia
- One dog that loves me, one cat that chooses
to be nice to me sometimes
- Professional question asker, generally determined 
to get to the bottom of things :thinking:
- Started in psychology, now a general data analyst
- [Lifelong learner](#Certifications)

### Recent projects :man_technologist:

I like to stay busy and try out new tools (and/or just 
play with data). Most recently, I've been working on:

#### [Solving Squirdle](https://github.com/zloomas/squirdle-solver)
- [Squirdle](https://squirdle.fireblend.com/)
is the Pokémon response to Wordle, where you guess a Pokémon
and get feedback on how your guess compares to the secret
target Pokémon.
- I've played at least one game from every generation of the
series, but I'm an old man so I don't really know any Pokémon
after about Generation 4 (there are currently 8 generations,
with a 9th supposedly on the way at the end of 2022).
- It was driving me crazy to feel like I could never get
the target Pokémon if it came from Gen 5+, so I wanted to 
build an automated player to supplement the gaps in my knowledge. 
Then I wanted that player to actually be good,
so I tried to help it get any secret Pokémon in as
few guesses as possible.
- My patent-pending Squirdle Solver:tm: uses something like
a binary search approach to iteratively guess the median
Pokémon given the set of remaining possible guesses.
"Median" takes into account all 5 features that the game provides 
information about: generation, type 1, type 2, height, and weight.
- Pro tip: start with 
[Simipour](https://bulbapedia.bulbagarden.net/wiki/Simipour_(Pok%C3%A9mon))! 
:droplet::monkey:

#### [Exploring the COS collaboration network on OSF](https://github.com/zloomas/COS-OSF-Network-Analysis)
- Used data from the Open Science Framework
to profile the collaboration network of current staff 
(in March, 2022) at the Center for Open Science.
- Data was gathered via the [OSF API](https://developer.osf.io/)
(thank you amazing devs for amazing docs!) using the requests
module in Python.
- Storage managed locally in a SQLite DB.
- Analysis and [report](https://github.com/zloomas/COS-OSF-Network-Analysis/blob/main/COS_OSF_collaboration_network.ipynb)
done in Jupyter Notebook with pandas and matplotlib.

#### [Visualizing the career of Mark Davis, PhD](https://github.com/zloomas/davis-career-viz)
- Used data from Web of Science to create a citation network
visualization centered on Dr. Mark Davis.
- Mark is a family friend who retired from a career as a 
research psychologist in 2020, and this was his Christmas
present to commemorate his impact in the literature.
- Data was gathered manually from WOS then processed 
in Python with pandas.
- Visualizations created in R using ggplot2 enhanced 
with ggraph.

### Certifications
- [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
| Udacity | In progress, expected completion June, 2022
- [Data Engineer](https://www.dataquest.io/path/data-engineering/)
| DataQuest | Completed April, 2022 | 
[Certificate](https://app.dataquest.io/verify_cert/SRMBPRU9B6FEMJ7J0U57/)
