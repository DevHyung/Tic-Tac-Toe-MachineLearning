# Tic-Tac-Toe-MachineLearning
======================
# 1. Project Name 'TIc-Phago'
## 1.1. Tic-Phago?
Tic-phago(Tic-Tac-Toe + Alphago) referred to ‘Tic-phago’

## 1.2. What the Tic-Tac-Toe
Tic-Tac-Toe is the game that two people play alternately. To start the game you have to select one of O and X shapes. It is a game each person draws a figure and puts one’s figure on a horizontal, vertical, or diagonal line. The person who completes the figure line first, wins. It is m, n, k-game, and (3,3,3)-game.
Below is an example when X wins first place.
![tictactoe](https://github.com/DevHyung/READMEIMG/blob/master/tictactoe.png)
## 1.3. Project Description
Developed ‘Tic-Phago’ based on the rules of the game titled "Tic-Tac-Toe", which is a program that achieves three consecutive horizontal, vertical and diagonal lines of O or X. Because there are only nine boxes, the number of possible cases of play is likely to exceed a maximum of 9! = 362880, but by the order of the words (O is the first or X is the first).
The training data is less than the number of nodes in all the trees with approximate 3 ^ 9 = 19683 branches and 9!(actually less then 9!) leaves. Because if there is already a win, and the game is clear, subsequent tree nodes are meaningless, and there is no need to increase if obvious draws are expected. Also, the beginning of the case of O and X seems to be different, but it can be virtually the same due to the symmetric relationship. 'Tic Tac Toe' is an unconditional draw if you do your best. Therefore, it is aimed to be tic-tac-phago in the game between the 'Tic-phago' is to draw and the ‘Tic-phago-to-person game, the goal is to set an additional rule and win.
## 1.4. Data Description
There is no data, available from the ‘sampled data center’ or ‘data lab’. Thus, the AI Tic-tac-toe prefer to develop first. Continue the confrontation between 'Tic-tac-toe AI' and save it in database and learn the data in ‘Tic-phago’. This method uses the 'Alphago Zero' method without learning even the basic data. It is not the same as ' Alphago Zero', but it learns and uses the data obtained from the confrontation between AI and the machine. See the below picture
![tictactoedata](https://github.com/DevHyung/READMEIMG/blob/master/ticdata.png)
# 2. Development environment
## 2.1. Testing
Tested on windows with Python 3.6 (packages numpy, tensorflow and flask are required)
## 2.2. Development Spec
```
CPU : intel i5 - 6600
RAM : 16G
OS  : windows 10 pro
GPU : nvidia GeForce 960 8G
```
# 3. How To Use
## 3.1. File Description
```
1. AI_VS_AI_TICTACTOR.py : Ai versus Ai so making a data-set , Here, can see the process that occurred data-set but remove the file I / O part.
2. GUI_TICTACTOE.py : Ai versus Human GUI version
3. Learned_TICTACTOE.py : machine learning TICTACTOE script file use this
```
## 3.2. Command
```python
# after required package install (ex: tensorflow, numpy, etc... )
# if you are first start, Line 176 e = epsilon
# else (you are not first excute ) e = 0 setting 
py -3 Learned_TICTACTOE.py
```