# Unit 1: A classic game 
![](game.gif)

# Criteria A: Planning

## Problem definition

The owner of the local game shop is an enthusiast of classic computer games. He has been looking for a talented programmer that can help him revive his passion for text-based games. He has few requirements for this task:

1. The game has to be entirely text-based.
2. The game must record the time played.
3. The game must record the player name and score.
4. The game recreates the tale of the Iliad based on your story choices (you play as the greeks)
Apart for this requirements, the owner is open to any type of game, topic or genre.

In terms of existing products, there are many games based around the Trojan war. However, most of these games simply take characters and famous features such as the Trojan horse and Achilles battle with Hector. My game hopes to present a more linear, storylike version of the game for the player. Rather than just fighting NPCs the player should be able to enjoy the story and think about their decisions regarding the plot. If the player follows the path accurate to the original story, I hope they can learn something new. If not I just hope they can come to appreciate the classics more.

## Proposed Solution
For my proposed game the player will play as Achilles from the Iliad. The aim of the game is to defeat the Trojans as soon as possible, disregarding history.  The client wishes to have a fully text based game that records the time played and a score. The score is based on the decisions you make. The quicker you end the war and the more lives you save the higher the score. The game will be considered a success when you can complete the entire story and receive a score. The application will receive the player’s input and decide whether or not the player would succeed in the game. The program will deduct points when your companion Patroclus is killed. In the end the player with the fastest time and highest score is ranked first. The game ends when the Greeks successfully deliver the Trojan horse to the gates.

I will to design and make a text based video game for a client who is an old game store owner (or in this case Dr Ruben). The text based game will about Homer's Iliad and is constructed using the software Python. It will take a few months to make and will be evaluated according to the criteria listed below.


## Success Criteria
The game should include 3 key stages. The first battle which leads into the plauge, the second battle which leads to Achillies withdrawal from battle and the final stage where the player aims to lead the Greeks to victory. The score system should have medals. One where you get the worst possible ending with the lowest socre possible (-100), one for the highest score possible (100) and one for a perfect 50/50 score. The game should only take input as integers and the character you play as should be Achilles. 

# Criteria B: Design

## System Diagram
![Screenshot (9)](https://user-images.githubusercontent.com/89110625/138578924-0f47e7cc-7616-47f6-b005-7d90a88b541d.png)
Fig 1. System Diagram of proposed solution
In this diagram, my program will use keyboard inputs and python programming to run my proposed solution. The output will be text on your screen.

## Flow Diagrams
<img width="640" alt="Screenshot 2021-10-24 at 12 10 02" src="https://user-images.githubusercontent.com/89110625/138580433-23ec2f96-f4b5-408c-8ae1-daf0286bdd64.png">
Fig 2. Flow diagram of Arc 1 and part 1 of Arc 2
The diagram shows the rough paths and decisions the player will see and make in the game in Arc 1 and the first part of Arc 2

![Screenshot 2021-10-24 at 13 34 28](https://user-images.githubusercontent.com/89110625/138582265-31ed6395-e513-44f0-b3c1-87b479c3453d.png)

Fig 3. Flow Diagram of Act 2 part 2 and Act 3
The diagram shows the latter half of Act 2 I have in mind and the final Act.

Link to MVP (repository):https://colab.research.google.com/drive/1W_60-8gPe4MbYQOvwGOqgvI6l7wVUebe

MVP Video (short):


https://user-images.githubusercontent.com/89110625/138581636-488f692e-ae2a-487b-96f8-e80a2515eeee.mp4



## Record of Tasks
| Task Number | Action                    | Outcome                                                                                                                                     | Target Time and Date | Criterion   |
|-------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------|-------------|
| 1           | Systems diagram           | Have a clearer understanding of my game's structure                                                                                         | 10mins (Sep 23)      | B           |
| 2           | Planning and Plot         | To know what my game is about and have information to provide to my client about the overall game idea.                                     | 30mins (Sep 27)      | B           |
| 3           | Flow Diagrams             | create the first few flow diagrams to aid in the creation of the final game                                                                 | 80mins (Sep 30)      | B           |
| 4           | Begin programming         | The first section of the game should be coded to test the structure. This allows me to know if the structure will work throughout the game. | 50mins (Oct 1)       | C           |
| 5           | create encoder            | required for the game, mostly to protect any user inputs with personal information                                                          | 30mins (Oct 7)       | C           |
| 6           | test encoder              | make sure out encoder works                                                                                                                 | 5mins (Oct 7)        | E           |
| 7           | MVP                       | Have a minimum viable product finished (*note submission failed so no feedback is given, the video will be uploaded to repository)          | 30mins(Oct 15)       | C and E (?) |
| 8           | Act II                    | The development of Act II is underway and should at least be partially finished by the 25th                                                 | 120mins (Oct 19)     | C           |
| 9           | continue game coding      | Progress is slower than expected and I believe I have overestimated myself, It doesn't seem I can finish the game on time                   | 60mins (Oct 22)      | C           |
| 10          | Final Edits to Repository | Since criterion A and B are the priority more time will be spent making sure those aspects are up tp par                                    | 120mins (Oct 23)     | A and B     |
| 11          | Reflection                | I wanted to write down my thoughts on the process and how I could improve since I left much to be desired.                                  | 20mins (Oct 24)      | D (?)       |
| 12          | Rework               | I had a breakthrough and wish to continue as much as possible. I know given previous progress I'm not sure I can finish but I do believe I can improve it.                                  | 120mins (Oct 24)      | C       |
| 13          | tesing              | testing of the game should be carried out by playing the game and running the program. Besides isolating sections of code to test them, I also plan to run the program and run the debugger to make sure nothing is wrong.           | 20mins (Oct 25)      | E(?)       |


## Product
First MVP:https://github.com/VickyhqL/unit_1-2021/blob/main/Gamemvp(foldered).py
I can't upload the pycharm(.py) file sorry! 

Final Finished game (Incomplete I want to perfect it)

## Testing Table
| Description                   | Type        | Input                                              | Expected output                                                                   |
|-------------------------------|-------------|----------------------------------------------------|-----------------------------------------------------------------------------------|
| Testing name and score system | Unit        | PLayer name (eg Atlas) and choices                 | Player name (Atlas) and final score(-120 to 120)                                  |
| Testing the first Act         | Integration | Player name and all their choices (numerical form) | Player name and story's plot                                                      |
| MVP testing                   | Code Review | Player name, choices                               | The full first act of the story,score as of first act, time taken and player name |
| Cipher testing                | Unit        | Player name (eg Atlas)                             | player name encrypted (eg. dwodv)                                                 |
| Timer testing                 | Unit        | Game choices                                       | Story and Time taken printed as "Your total game time is :"                       |

## Reflection
Personally I feel that I did not manage my time correctly. I underestimated the time I needed to program the game itself and my inital idea for a score system proved difficult to execute. As such I tired to simplify it. Even then it didn't turn out well. I personally feel my time management was lacking and I was too ambitious given my limited knowledge in programming thus far. In the furutre I would benefit from makng a more detailed plan of my game and spend more time fufilling the success criteria rather than chasing after my chosen plot ideas. Since I spent so much time trying to flesh out the story one of the key requiremnts of haveing a score system ended up mostly unfinished.


*As of the 24th I suddenly made a breakthrough with the score system and my code. It is now undergoing a rework. I was overcomplicating what I needed to do. The program will see some changes until it is finished. Given the rework it is unlikely I can complete and start Act 3 before Monday even though time is up.

| ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ | ฅ ̳͒•ˑ̫• ̳͒ฅ |
##Improved versions of old stuff (like them flow diagrams)
