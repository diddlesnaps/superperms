# Search for minimal Super Permutations

Search for minimal Super Permutations as part of a distributed computing project. More information can be found in these videos:

- [Numberphile](https://www.youtube.com/watch?v=wJGE4aEWc28)
- [Standupmaths](https://www.youtube.com/watch?v=OZzIvl1tbPo)

[This article](https://www.quantamagazine.org/sci-fi-writer-greg-egan-and-anonymous-math-whiz-advance-permutation-problem-20181105/) in Quanta magazine also explains.

The search is based upon these research papers:

- [Nathaniel Johnston](https://arxiv.org/abs/1303.4150)
- [Robin Houston](https://arxiv.org/abs/1408.5108)

This snap was created by the Ubuntu Podcast community. We would be grateful if you could join the "Ubuntu Podcast" collective for this search so we can "win", but this is optional. Please also give the Ubuntu Podcast a listen in your podcatcher or at [the UbuntuPodcast Website](https://ubuntupodcast.org/), and maybe [join The Ubuntu Podcast Telegram chatroom](https://ubuntupodcast.org/telegram/).

[Statistics for the search and team leaderboard](http://www.supermutations.net/ChaffinMethodResults/).

To run with your team set to Ubuntu Podcast:

`superperms team "Ubuntu Podcast"`

The default team is "Anonymous".

You can tell the program to run for a specified number of minutes, after which it will **wait to finish the current task before quitting**:

`superperms timeLimit 120 team "Ubuntu Podcast"`

This would tell the program to run for 120 minutes and then quit, **after it has finished its current task**.

You can also enforce a stricter time limit, using the option timeLimitHard:

`superperms timeLimitHard 120 team "Ubuntu Podcast"`

With this the program will run for 120 minutes and quit, within about 5 minutes of that quota, **even if** it is in the middle of a task.

A single client will use one CPU core, so if you want to dedicate more CPU time to the search you need to run the client multiple times - the standard is to run one client per CPU core in your PC.

This app will eat batteries on a laptop or tablet computer so it is advisable not to run this on such devices if they are not plugged-into a stable power outlet. The search will also produce a lot of heat.

[The source code for this client is on GitHub](https://github.com/superpermutators/superperm).

[Ongoing discussion about the search is held in the Google Group](https://groups.google.com/forum/#!forum/superpermutators).