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

## Updates (10/24/2021)
I have uploaded an updated version of the Wheel of Fortune Notebook file. I have made the following updates to the code, mostly pertaining to the final round (note that some issues and bugs listed below may still be present):
1. The code now reveals "R-S-T-L-N-E" instead of just "R-S-L" in "MARBLES".
2. You will lose the game once you have guessed 3 consonants and 1 vowel. You will not have an opportunity to make guesses after this point (the input box will not be present).

## Coding Issues & Bugs (09/27/2021)
The following are a few coding errors and bugs that you may come across when running the code:
1. The way I structured my code made it not be programmed to lose money/end turn after the wheel lands on "Bankrupt" or "Lose a Turn". You will need to rerun the code in order to properly finish the game.
2. The program continues to add money for each iteration of a letter. For instance, if the wheel spins 500 and there are two instances of the letter "E" in the word, the player will win a total of 1,000 instead of 500.
3. After winning the game, the input box is still present. **(10/24/2021: This has been fixed in the update.)**
4. Sometimes the player's name doesn't display properly in the final round. For instance, "Congratulations, ! You have made it to the final round!" or "Congratulations, eric! You have made it to the final round!" It doesn't happen every time.
5. The way I wrote the code for each round is outrageous and is probably the reason why all these bugs are happening.
