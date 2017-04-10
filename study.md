# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.

      Have been sketching it in my moleskin. Will upload to imgur if necessary.

-   The data structure you plan to use.

      HTML/CSS/Javscript/Ajax/Game API
      I'm not sure exactly what this is asking

-   How you will take the markup of the game board and represent it in JS

      I think I will represent each spot on the board (1 through 9) and then have three conditions for each spot that are stored by the engine/backend-- empty, filled with x, willed with o.
      There are only a certain number of winning conditions, so I will list those out and if *either* all x's or all o's make up one of those winning conditions after a turn, then the game is over and it will announce who won. Each time someone moves, it will check the *filled* spots on the board against the winning conditions, for both x's and o's.


-   How you plan to approach this project.

      I'm going to plan out in writing/pseudo-code everything that the game engine needs to do, including all communications with the back-end that need to occur. Then I'm going to start listing the relevant code underneath each of those steps, including the ajax/json/api stuff (most importantly). Then I'm going to start coding and make sure that I have the bare bones engine of a game that works. Hopefully I'll be finished with this with enough time left that I can make it look pretty/possibly take a hack at the bonus goals.

-   4-8 user stories for your game project.

      1. As a user, I would like to be able to sign in/ choose x or o, and have a friend do the same
      2. As a user, I would like the game board to tell me whose turn it is.
      3. As a user, I would like the game to rerspond snappily to my clicks when I choose a spot on the board
      4. As a user, I would like it to tell me which player won once the game is complete
      5. As a bonus, it would be cool if the game kept a win counter for the session, as well as my all-time record as a user--- wins, losses, draws

-   How you plan to keep your code modular.

      I'm gonna keep interactions with the API, user events (making moves), the UI of the board/site, the sign-in/sign-out section, and all the CSS stuff in different files that link to each other (modular).

-   What creative spin will you add to your project?

      At the very end, I might add an ability to play against the computer, where the "computer" chooses random spots to place its move after the player moves. Extra extra credit might be to make the computer a bit better at the game than "random", but I would need lots of extra time to do this.


-   How will you use version control to backup / track your project?

      I think I'll make frequent commits with messages explaining what I did. I'm going to keep the working game engine on its own branch, and any changes to it that I implement in pursuit of the bonus goals will go on its own branch so that I don't accidentally break my working engine. I'm pretty paranoid, so I'm confident that I'll be thorough. I will make frequent backups and redundancies as well.

-   Do you plan to attempt any of the bonuses?

    If I finish the working game with at least a day left, the most likely bonus that I'll pursue is interesting/pretty styling. If I finish that in time as well, I may try to implement the ability to keep track of game rounds with a win counter/etc. That's as far as I've gotten in terms of planning.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
