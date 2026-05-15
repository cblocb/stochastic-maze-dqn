# stochastic-maze-dqn

this was my deep reinforcement learning project for eece 5614

the environment is a stochastic maze where actions do not always move the agent exactly in the intended direction, and some cells have penalty costs

for the project i implemented:

- standard dqn
- double dqn
- dueling dqn

the state representation was just the normalized `(x, y)` coordinates of the maze position, and the network learned q-values for the four movement actions

the repo includes:

- `project4.ipynb` with the implementation and experiments
- `project4_report.pdf` with the submitted writeup
- a few extracted figures from the final report

what i compared:

- training reward / loss trends
- average episode length
- effect of learning rate
- final learned policy / values / sampled path

main result:

all three methods learned a valid path through the maze. standard dqn already worked well, double dqn gave the best final reward in my implementation, and dueling dqn had the cleanest final loss.

the report has the exact setup, hyperparameters, and final numbers.
