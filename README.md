# Pokemon Card Game


Pokemon Card Game is a multi-level memory card game developed in Java with [kilt-graphics API](<https://mac-comp127.github.io/kilt-graphics/>) to enhance concentration and critical thinking skills in 5-8 youth. It was developed by: 
James Hernandez, Linh Nguyen, Na Nguyen

<img width="888" alt="Screenshot 2023-12-10 at 5 05 32 PM" src="https://github.com/Mac-COMP-127-Fall-2023/course-project-pokemon_cards-na-linh-james/assets/134335069/639800cc-11f8-4d18-837a-f673b2d543c0">
<img width="888" alt="Screenshot 2023-12-10 at 4 59 06 PM" src="https://github.com/Mac-COMP-127-Fall-2023/course-project-pokemon_cards-na-linh-james/assets/134335069/ee0072e4-d26a-4eee-a908-fbb74e3874e0">
<img width="888" alt="Screenshot 2023-12-10 at 5 05 42 PM" src="https://github.com/Mac-COMP-127-Fall-2023/course-project-pokemon_cards-na-linh-james/assets/134335069/2a9f9a88-50e5-4482-826b-0f9e973d1a6d">

The game has 3 levels of difficulty: easy (5 pairs, 10 attempts), medium (10 pairs, 20 attempts), and difficult (15 pairs, 30 attempts). The game begins with all cards flipped upside down. Upon clicking one of the cards, it flips face-side-up to reveal the pokemon it pertains to. The goal of the each round is to find the matching card, with 15 total pairs, for the card flipped. Upon the second card being clicked, if it is not a correct match, the cards will flip back over to hide the pokemon. However, if they match, the two cards will be removed from the screen. The goal of the game is to remove all pairs before the given time and under the limited number of attempts.


## UML Diagram
Below is a UML Diagram of our classes, their variables, methods, and their relationships.

<img width="700" alt="Screenshot 2023-12-10 at 5 15 27 PM" src="https://github.com/Mac-COMP-127-Fall-2023/course-project-pokemon_cards-na-linh-james/assets/134335069/4f6b2074-5336-4c13-91cf-4d637232feab">


## Game UI features
Use [kilt-graphics API](<https://mac-comp127.github.io/kilt-graphics/>) to generate a grid whose size is dependent on the difficulty setting, holding a level-determined pairs of pokemon graphics cards. The position of all 30 graphics images are randomly generated. 



## Technical Guide: 
The technical requirements of this game are minimal, only having Java 17 installed. To play the program, users should refer to the PokemonCardGame class and run the main method.


## Acknowledgements: 
We got the inspiration from the Vietnamese card game "Noi hinh Pikachu". This source-game is similar in that cards must match, but has different logics and rules. 

Our pokemon card images come directly from the pokemon official pokedex website, which has images and information on all 406 pokemon. (<https://www.pokemon.com/us/pokedex>). 

The winning image comes from a GeekySweety blog post that ranks pokemon art based on cuteness. (<https://geekysweetie.com/my-favorite-pokemon-ranked-by-cuteness-cutest-pokemon-ranked/#>)

Our image for losing comes from Tynker, an online porgram that helps teach children to code (<https://www.tynker.com/community/projects/play/pokemon-battle/5d4e7a20cebfbd358676cd13/>). This image was created by a user named Stylish Lupin. 

With the use of a Youtube Channel "Coding with John," we were able to find information on Threads, which was very helpful for creating our timer. We did not use everything, but it gave us a bit of familiarity with the concept. (<https://www.youtube.com/watch?v=r_MbozD32eo>). We also used ChatGPT (<https://chat.openai.com>) to help with this, giving it the promt: (<“how to add a timer that counts down 5 minutes on the screen the moment the game runs”>).

We added music from the 1997 game. We donloaded this music from a CD website, khinsider. We compiled four of these songs - guide, cycling, Pewter City, and Casino - with the audio editing program Audacity to merge 4 songs to make a compilation of at least 5 minutes (<https://downloads.khinsider.com/game-soundtracks/album/pokemon-game-boy-pok-mon-sound-complete-set-play-cd>). To add music, we watched a youtuber Max O'Didily (<https://www.youtube.com/watch?v=wJO_cq5XeSA>). To help create a loop, we asked ChatGPT "How to loop through an audio in Java" (<https://chat.openai.com>). 

Our button images come from The Noun Project, which has a large selection of stock/ .png images (<https://thenounproject.com/>). 

We documented our sources throughout the code, but we wanted to give special mentions to Stack Overflow, Youtube, ChatOpenAI, as well as Nam Nguyen (class of 2023) for his general help. 

## Known Issues:
Using kilt.graphics as the basis for its GUI, Pokemon Memory Game has certain limitations in advanced graphical animations that can be achieved by using other packages such as Swing. There are no specific bugs, glitches, or shortcomings that users should be aware of as of today. 


## Societal Impact:
Pokemon Memory Game relies entirely on mouse clicks for user input and screen navigation. This creates barriers for those who rely on keyboards and switches to access computers and other digital devices. 
Furthermore, taking into consideration the different colors of pokemon characters against the card background, Pokemon Memory Card does not comply with the AAA color contrast guide which imposes strain on those with low vision and color blindness. 






