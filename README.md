# stochastic-maze-dqn

deep reinforcement learning on a stochastic maze

this was my dqn project for rl class

i implemented:

- standard dqn
- double dqn
- dueling dqn

the maze is stochastic, so the intended action doesnt always happen exactly, and there are penalty cells / walls / a goal state

i used normalized `(x, y)` coordinates as the state input and learned q-values for the 4 movement actions

mostly i was comparing how the different dqn variants trained and what kind of final policies they learned

double dqn ended up doing the best in my runs, but standard dqn also worked pretty well and dueling dqn had the cleanest final loss

the notebook is here, the submitted writeup is `project4_report.pdf`, and i also left a few figures from the report in the repo
