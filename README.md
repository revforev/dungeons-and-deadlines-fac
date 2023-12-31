
I. Introduction

Dungeons & Deadlines is a Role Playing Game that blends elements of Roguelike, RPG and Point & Click Adventure. 

"The year is 2006 and you're a Web Designer.
Life's nice and simple. You haven't landed your first job, but your local fame 
attracts some freelancing work for you.
The internet is super slow. Parties are great. You're always on the road. 
The only question is: can you pay the rent by the end of the week?"

I wanted to make a game that would make you into believe that day-to-day life is more interesting than it seems.
The game timespan is one week. You start on a Monday, and each stage represents a day of the week.
You can win the game by aquiring 12 coins before the next Monday. If you do not aquire 12 coins by the end of the week, you still get to pay the rent and "win" the game, by triggering one of the 3 alternative endings (depending on your stats).
The main takeway point of the game is "the journey is more important than the destination. Never give up".




II. Usage

1. Open the website.
2. Click on the "Start" button.
3. Use your mouse to click on the answers.
4. Don't worry about getting it right! You can't loose.
5. Relax and enjoy the game.
6. Start over for a different outcome!






III. Mechanics

The rules of the game are easy.

There are 3 possible starts, depending on the time of the day the game is played. There is a morning start, an afternoon start and an evening start - each with different outcomes, questions and answer options.

You start the game on Monday, each of the 7 levels is a coding challenge (a question), representing a day of the week, with the final boss (RENT) due to next Monday.

Coding questions are randomised each time on startup. This is done using 5 objects of 10 questions each from variuous degrees of difficulty. The questions are HTML for the lower levels, then CSS and then Javascript.

You start with 0 coins. There are 7 challenges. Each will give out 3 coins. You need 15 coins in order to pay the rent.

There are 3 types of levels: code challenges, mystery events and fuel stations.

The mechanics of the game are governed by 3 stats: Energy, Flex/Health and Internet Speed. These are shown in the interface on the top left corner. These stats function like classes currently, as in they determine the outcome of the game. Stats are currently aquired at the beggining of the game, depending on the user's answer to the first 2 questions.
For example: choosing to "go for a run" 

The other in-game currency is simply coins.

I wanted to practice Javascript objects and functions, so I used the Math object, randomising things, keeping a stats system in arrays and objects and used the user's date & hour to make the game experience more immersive.

The game uses a navigator function in order to display frames, or stages. There are 25 stages which are stored in an array, and they are being navigated on a next/previous basis, using a function that is bound to an onclick attribute on button elements.

At the moment, there are 4 ways to win and there is no way to lose. This is due my philosophy which was - I would rather create a world to be explored, and generate curiosity - rather than simply test people's coding skills. There are enough good outlets for that already!

The game can be won by following the rules and aquiring 15 coins! If the 15 coins are not aquired, the highest stat will determine the outcome in the 7th day.

For instance: if the highest stat is Internet Speed, this will trigger the Internet Speed Ending - which is an outcome where you get to pay the rent with the help of a neighbour that you let use your internet to work! He then helps you pay the rent - this is the Internet Speed ending.







IV. Conclusion

I think most of us experience our daily activities as preparation for the future goals. The concept of this game is built around awareness for daily, mundane activities. This is an exercise in being present. I hope you have enjoyed the game, and thank you for your time!
