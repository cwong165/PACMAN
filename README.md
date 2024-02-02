# UCB Pacman Project - Search Algorithm Implementation 🎮

## Overview
This project is part of CS205 and involves implementing search algorithms to help Pacman navigate mazes and find food efficiently.

## Procedure
- Week 5: Implementation of DFS and BFS to help Pacman find a fixed piece of food.
- Implement Questions 1-2:
  -  Attach Images (TODO)
- Implement Questions 3-4:
  -  Attach Images (TODO)

## Implementation Details
Details will be provided as the project progresses. (TODO)

## Auxiliary Questions
- Does Pacman visit all the explored nodes? 
  -  No, Pacman doesn't need to explore all nodes; while DFS might not be optimal, it does not explore every single node on the grid but instead follows a path until it reaches the goal or a dead end.
- Is DFS a least-cost solution? 
  -  No, DFS is not guaranteed to provide a least-cost solution. It explores paths arbitrarily without considering the cost, which can lead to suboptimal paths with higher costs than necessary. For example:
      - If there are multiple paths to the goal, DFS might explore a longer, costlier path due to its depth-first nature, potentially missing shorter and less costly paths.
      - DFS prioritizes exploration depth over path cost, which means it may reach the goal efficiently in terms of the number of states explored but not in terms of the overall path cost.

---
**Note**: Most sections are currently left blank and will be completed as the project progresses. This is an add-on project for UCB, and the content will be updated with specific details and images as we answer more questions.
