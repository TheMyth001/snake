# snake
Learning Snake using Deep Q-Learning

## state space
- direction of snake head (4 one-hot features)
- direction of food from snake head (4 one-hot features)
- obstacle array (array of the board - 1 for obstacles, 2 for snake head, 0 elsewhere)

## reward function
- +1 for moving closer to apple
- -1 for moving away from apple
- +10 for eating apple
- -20 for dying

## action space
- straight
- left turn
- right turn
