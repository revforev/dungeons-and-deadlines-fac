$$$$$$$\                                                                 
$$  __$$\                                                                
$$ |  $$ $$\   $$\$$$$$$$\  $$$$$$\  $$$$$$\  $$$$$$\ $$$$$$$\  $$$$$$$\ 
$$ |  $$ $$ |  $$ $$  __$$\$$  __$$\$$  __$$\$$  __$$\$$  __$$\$$  _____|
$$ |  $$ $$ |  $$ $$ |  $$ $$ /  $$ $$$$$$$$ $$ /  $$ $$ |  $$ \$$$$$$\  
$$ |  $$ $$ |  $$ $$ |  $$ $$ |  $$ $$   ____$$ |  $$ $$ |  $$ |\____$$\ 
$$$$$$$  \$$$$$$  $$ |  $$ \$$$$$$$ \$$$$$$$\\$$$$$$  $$ |  $$ $$$$$$$  |
\_______/ \______/\__|  \__|\____$$ |\_______|\______/\__|  \__\_______/ 
                           $$\   $$ |                                    
                           \$$$$$$  |                                    
                            \______/                                  

 $$$\     
$$ $$\    
\$$$\ |   
$$\$$\$$\ 
$$ \$$ __|
$$ |\$$\  
 $$$$ $$\ 
 \____\__|
          

$$$$$$$\                         $$\$$\$$\                            
$$  __$$\                        $$ $$ \__|                           
$$ |  $$ |$$$$$$\  $$$$$$\  $$$$$$$ $$ $$\$$$$$$$\  $$$$$$\  $$$$$$$\ 
$$ |  $$ $$  __$$\ \____$$\$$  __$$ $$ $$ $$  __$$\$$  __$$\$$  _____|
$$ |  $$ $$$$$$$$ |$$$$$$$ $$ /  $$ $$ $$ $$ |  $$ $$$$$$$$ \$$$$$$\  
$$ |  $$ $$   ____$$  __$$ $$ |  $$ $$ $$ $$ |  $$ $$   ____|\____$$\ 
$$$$$$$  \$$$$$$$\\$$$$$$$ \$$$$$$$ $$ $$ $$ |  $$ \$$$$$$$\$$$$$$$  |
\_______/ \_______|\_______|\_______\__\__\__|  \__|\_______\_______/ 

                                                                      
                                                                      
                                                                     
          Table of Contents

  ┏━━━━━━━┳━━━━━━━━━━━━━━━━━┓
  ┃   I   ┃    Introduction    ┃
  ┣━━━━━━━╋━━━━━━━━━━━━━━━━━┫
  ┃   II  ┃    Usage           ┃
  ┣━━━━━━━╋━━━━━━━━━━━━━━━━━┫
  ┃   III ┃    Mechanics       ┃
  ┣━━━━━━━╋━━━━━━━━━━━━━━━━━┫
  ┃   IV  ┃    Contributing    ┃
  ┣━━━━━━━╋━━━━━━━━━━━━━━━━━┫



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
The main takeway point of the game is "the journey is more important than the destination, never give up".




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







IV. Contributing

Main reason behind this game is I believe people are not able to experience their day-to-day moments as real, unique experience, as all-that-is-out-there experiences. But rather as preparation for the future goals. This is an exercise in being present.

The other reason is me wanting to practice Javascript during one summer and looking to hone my skills, so that I could one day work with other people on bigger projects. I hope you see this as an opportunity to hone your own skills aswell, as there is much more work to be done here!

One of the first things this needs doing - and your help would be much appreciated and change the project a ton - would be making it responsive!

This could be done fairly easy using media queries on the few elements it has.

Please feel free to jump in and contribute!
1. Fork the repository.
2. Clone your fork: `git clone https://github.com/yourusername/your-game-app.git`
3. Create a new branch for your feature or bugfix: `git checkout -b feature-name`
4. Make changes and commit them: `git commit -m "Description of changes"`
5. Push the branch to your fork: `git push origin feature-name`
6. Create a pull request on GitHub.


Give me a shout over Github or drop me an email at dutulescu_andrei@yahoo.com


