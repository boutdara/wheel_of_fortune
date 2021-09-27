# Wheel of Fortune

## Introduction
This repository contains my plans and code for Week 6 of the Dev10 Development Program. We were tasked to simulate a Wheel of Fortune game using Python. For my game, the category is "Childhood Games" and the phrases used for each round are listed below (these are also listed inside the code for each round but not visible during gameplay):

<details>
  <summary>Round 1</summary>
  
  ```javascript
  REDLIGHTGREENLIGHT
  ```
</details>

<details>
  <summary>Round 2</summary>
  
  ```javascript
  TUGOFWAR
  ```
</details>

<details>
  <summary>Round 3 (Final Round)</summary>
  
  ```javascript
  MARBLES
  ```
</details>

## Coding Issues & Bugs
The following are a few coding errors and bugs that you may come across when running the code. I'm sure that there are more errors that I haven't noticed, so I would be grateful if I am notified of any additional errors so that I may update it in the future!
1. The way I structured my code made it not be programmed to lose money/end turn after the wheel lands on "Bankrupt" or "Lose a Turn". You will need to rerun the code in order to properly finish the game.
2. The program continues to add money for each iteration of a letter. For instance, if the wheel spins 500 and there are two instances of the letter "E" in the word, the player will win a total of 1,000 instead of 500.
3. After winning the game, the input box is still present.
4. Sometimes the player's name doesn't display properly in the final round. For instance, "Congratulations, ! You have made it to the final round!" or "Congratulations, eric! You have made it to the final round!" It doesn't happen every time, but it's annoying when it does happen.
5. For some reason, if Player 3 (in Round 2 only) guesses incorrectly, it moves onto Player 1's turn (or so I think it does) but still displays Player 3's name.
6. No File I/O due to time constraints.
7. The way I wrote the code for each round is outrageous and is probably the reason why all these bugs are happening.
