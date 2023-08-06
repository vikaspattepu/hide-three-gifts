# Hides three gifts

This is a simple game where you have to find three gifts in a grid. There are three levels in this game. You can select the level and start playing. There are three types of boxes in the grid. One is gift box, one is danger box and one is miss box. If you click on the gift box then you will get one star. If you click on the danger box then you will lose the game. If you click on the miss box then you will get nothing. You have to find three gifts in the grid to win the game. If you find three gifts then you will get three stars.

# Demo

## https://venith-huggina.github.io/hide-three-gifts/

![image](https://user-images.githubusercontent.com/84177920/198501831-0a3eb329-8121-4cc3-b3f1-89745e669115.png)

# functions

## randomizeGrid(gridSize)

This function will return an array of random values. The length of the array will be the square of the gridSize. There will be three gift boxes, one danger box and the rest will be miss boxes.

## changeGrid()

This function will change the grid according to the selected option in the select box. It will call the randomizeGrid function and then create the grid according to the array returned by the randomizeGrid function.

## clrGrid()

This function will clear the grid.

# How to run the project

- Clone the project `git clone https://github.com/venith-huggina/hide-three-gifts.git`
- Open the `index.html` file in the browser



