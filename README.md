[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/o69wxeYp)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

> You can use this section of the file to keep notes about your project as you work on it.


# Project Summary

I made a 2 player version of Ultimate tic tac toe with colour changing buttons. It is tic tac toe but larger and more complex. The program tracks what player is playing and what board is playable based on the other players moves. 
When a board is won it turns to the winners colour and becomes unplayable. The game is won when the boards show a winning pattern. It is currently not possible to make a draw and the game will just be in a stand still. This goes for both the small boards and big board. 
- I had some troubles with the code. I didn't want to change the first code I wrote and instead fix the problems that appeared along the way. It was a little complicated fixing these problems using what I had learnt in this course. I searched up ways to fix my problems and also asked for help. I tried to fix them with my knowledge first. 
- I had a problem with the origina version of the winning function. It checked only one array and made it so you could win by placing a section of the winning pattern on multiple boards, instead of one board. I fixed this by assigning each of the buttons to its corresponding array and making the checkWinner function check each array. 
 - I had another problem with the BigBoard array not working at all and had to change the numbers to the arrays. This made it so the BigBoard array checked if the updated arrays inside it corresponded to a winning pattern. If an array is won it will update to either "blue" or "red".
- There was a follow up problem where the arrays wouldn't update correctly in the BigBoard array but that was fixed by moving the code into the for loop.
- There was no code for a draw but I wrote some and now you can get a draw on a small board and it wont show up as a playable board. You also get an alert when there is a draw on the big board. 
- If I had managed my time a little better I would code for a possibility to add a reset button and maybe a counter to see which player has won the most times. 
- I worked less than half of the budget. I started a bit late but finished the program in time as I had planned it. 


# User Guide

Ultimate Tic Tac Toe is similair to normal Tic Tac Toe but with a bigger board and a few more rules!
- Instead of playing on a singular board you play on 9 boards and your placement matters. The button you press dictates what board the next player can play. 
- For example: If you click the middle button in the middle row on any of the boards, the next player have to click a button in the middle board in the middle row and so on. 
- When you win a small board it will change the whole board to your colour. Your goal is to win 3 boards in a normal Tic Tac Toe winning pattern! 
- To reset the game you need to refresh the page.


