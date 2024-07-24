# Week 0 Search
- https://revisely.com/flashcards/packs/lmP6a
- https://colab.research.google.com/drive/1LVb9JNmMyWEMY3qTf5XeFCbtki3le3Ex#scrollTo=Lv7Rd_2SEyMM

# Quiz 0 - CS50's Introduction to Artificial Intelligence with Python
Quiz 0
------

Quizzes are _optional, but encouraged_. They are a good way to test your conceptual understanding, before diving into the programming projects. Consider each question below, then reveal the answer. If you didn’t get it right, consider why you may have had that misunderstanding!

Question 1
----------

**Between depth first search (DFS) and breadth first search (BFS), which will find a shorter path through a maze?**

*   DFS will always find a shorter path than BFS
*   BFS will always find a shorter path than DFS
*   DFS will sometimes, but not always, find a shorter path than BFS
*   BFS will sometimes, but not always, find a shorter path than DFS
*   Both algorithms will always find paths of the same length

Click here for the answer to Question 1

BFS will sometimes, but not always, find a shorter path than DFS

Question 2
----------

**Consider the below maze. Grey cells indicate walls. A search algorithm was run on this maze, and found the yellow highlighted path from point A to B. In doing so, the red highlighted cells were the states explored but that did not lead to the goal.**

![Quiz 0, Question 2](https://cs50.harvard.edu/ai/2024/quizzes/images/q0q2.png)

**Of the four search algorithms discussed in lecture — depth-first search, breadth-first search, greedy best-first search with Manhattan distance heuristic, and A\* search with Manhattan distance heuristic — which one (or multiple, if multiple are possible) could be the algorithm used?**

*   Could only be A\*
*   Could only be greedy best-first search
*   Could only be DFS
*   Could only be BFS
*   Could be either A\* or greedy best-first search
*   Could be either DFS or BFS
*   Could be any of the four algorithms
*   Could not be any of the four algorithms

Click here for the answer to Question 2

Could only be DFS

Question 3
----------

**Why is depth-limited minimax sometimes preferable to minimax without a depth limit?**

*   Depth-limited minimax can arrive at a decision more quickly because it explores fewer states
*   Depth-limited minimax will achieve the same output as minimax without a depth limit, but can sometimes use less memory
*   Depth-limited minimax can make a more optimal decision by not exploring states known to be suboptimal
*   Depth-limited minimax is never preferable to minimax without a depth limit

Click here for the answer to Question 3

Depth-limited minimax can arrive at a decision more quickly because it explores fewer states

Question 4
----------

**Consider the Minimax tree below, where the green up arrows indicate the MAX player and red down arrows indicate the MIN player. The leaf nodes are each labelled with their value.**

![Quiz 0, Question 4](https://cs50.harvard.edu/ai/2024/quizzes/images/q0q4.png)

**What is the value of the root node?**

Click here for the answer to Question 4

5
