# 🎲 Mini-game made in Python: throwing dice with the emperor 🎲

## Requisites
Python is the only requisite. It was made using Jupyter Notebook.

## The inspiration
This game is dedicated to Pedro, my teacher of Data Analytics, who always wanted that someone had the desire of programming an ancient game in Python.

## Rules of the game
The game is based in the informations of this <a href='https://www.getty.edu/education/college/ancient_rome_at_home/pdf/tali_tesserae_game.pdf'>link</a>.
'Tali' is the name of this ancient type of dice, with four positions instead of the usual six of current days. It was used in the Ancient Rome for betting games, such as the one developed in this project.
The game rules are simple: each player throws four Tali and, based in the results, have to bet a certain amount of money. Most of the results possible don't give any consequence, except for the following:

<table>
 <tr>
  <th>Value of the Tali</th>
  <th>Name of the Combination</th>
  <th>Value to Bet</th>
 </tr>
 <tr>
  <td>1-1-1-1</td>
  <td>Canis - The Dog</td>
  <td>3 pennies</td>  
 </tr>
 <tr>
  <td>All numbers the same (except 1), e.g. 3-3-3-3</td>
  <td>Vulture</td>
  <td>2 pennies</td>
 </tr>
 <tr>
  <td>6 and any other combination</td>
  <td>Senio - The Six</td>
  <td>1 penny</td>
 </tr>
 <tr>
  <td>Combination of the four possible numbers> 1, 3, 4, 6</td>
  <td>Venus</td>
  <td>The player wins the game! All the money betted is theirs now!</td>
 </tr>
</table>

## The Script
Using classes and functions, the game has the feature of playing how much time you want and how many players are interested. That means that aren't singular matches, but they are played how much time wanted and while the money of the players is still available. They decide how much they wanna put in the game and, if the money is over, they can add more, allowing them to do rematches.

## How it was played
Besides the fact that this game were played as a generic betting game - one of the favourite of the emperor Augustus! -, it could also be played as a drinking game! In that case, the player to first roll a Venus would be the arbiter and the master of drinking, preparating the ratio of water to wine. Besides that, the game were could be used for deciding any matters, specially those associated with the goddess Venus, ruler of all pleasurable things. Have fun!
