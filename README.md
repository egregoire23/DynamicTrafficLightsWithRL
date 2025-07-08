# Red Light, Green Light: Dynamic Traffic Lights with RL

The University at Buffalo's Medical Campus is located in a busy area in downtown Buffalo, where traffic lights are on a fixed pattern that does not allow for the complex reality of traffic flow. Through this project, my team seeks to improve the efficiency of traffic surrounding UB's Medical Campus by optimizing traffic light patterns using Reinforcement Learning.

Skills:

PyTorch, Model Evaluation, Public Speaking, Real-world problem-solving

Data:
- Single Intersection Traffic Data from SUMO-RL ([link](https://github.com/LucasAlegre/sumo-rl))
- UB Medical Campus Traffic Data from Open Data Buffalo ([link](https://data.buffalony.gov/Transportation/Annual-Average-Daily-Traffic-Volume-Counts/y93c-u65y/about_data))

Methodology:
- Built 3 RL agents from scratch (Q-Learning, SARSA, Double DQN)
- Utilized the PPO agent from the Stable-Baselines3 library
- Trained and evaluated all four agents on a simple single intersection
- Trained and evaluated the best-performing agents on the UB Medical Campus intersections
- Compared the overall best model with the current system in place (Fixed or Random Agent)

Tools & Technologies:
- Programming Language: Python
- Libraries: PyTorch, gymnasium, sumo_rl, stable_baselines3
- Software: Jupyter Notebook, GitHub, SUMO, Netedit

Results & Evaluation:

The Q-Learning agent provided the highest performance for optimizing traffic lights dynamically at UB's Medical Campus. Compared to the current baseline, our Q-Learning agent using dynamic patterns can reduce each vehicle's commute by more than 6 seconds at each intersection. These findings, if applied, could drastically reduce the average vehicle waiting time at the intersections in downtown Buffalo.

Challenges & Learning:

A big challenge to success on the UB Medical Campus map was that of the 19 intersections featured, each of which presented a different number of turn signal patterns, traffic flow directions, and number of lanes. Working through this hurdle greatly improved my ability to problem-solve in real-world situations. Additionally, I learned that complex problems like this can take days or even weeks to run, and time management is crucial when dealing with deadlines for such large tasks.
