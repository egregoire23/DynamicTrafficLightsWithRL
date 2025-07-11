# Red Light, Green Light: Dynamic Traffic Lights with RL

The University at Buffalo's Medical Campus is located in a busy area in downtown Buffalo, where traffic lights are on a fixed pattern that does not allow for the complex reality of traffic flow. Through this project, my team seeks to improve the efficiency of traffic surrounding UB's Medical Campus by optimizing traffic light patterns using Reinforcement Learning.

Skills:

PyTorch, Model Evaluation, Public Speaking & Presentation, Real-world Problem-Solving, Reinforcement Learning

Data:
- Single Intersection Traffic Data from SUMO-RL ([link](https://github.com/LucasAlegre/sumo-rl))
- UB Medical Campus Traffic Data from Open Data Buffalo ([link](https://data.buffalony.gov/Transportation/Annual-Average-Daily-Traffic-Volume-Counts/y93c-u65y/about_data))

Methodology:
- Developed 3 RL agents from scratch: Q-Learning, SARSA, & Double DQN
- Implemented the PPO agent using the Stable-Baselines3 library
- Trained and evaluated all four agents on a simple single intersection
- Trained and evaluated the top-performing agents on a full simulation of UB’s Medical Campus
- Compared the overall best model with the current system in place (Fixed or Random Agent)

Tools & Technologies:
- Programming Language: Python
- Libraries: torch, gymnasium, sumo_rl, stable_baselines3
- Software: Jupyter Notebook, SUMO, NetEdit, GitHub

Results & Evaluation:

Our Q-Learning agent achieved the best performance, dynamically adapting to real-time traffic conditions and outperforming traditional fixed-pattern systems. Simulations showed a reduction of more than 6 seconds in commute time per vehicle per intersection, highlighting the potential for real-world impact if such models were deployed city-wide.

Challenges & Learning:

The UB Medical Campus includes 19 intersections, each with unique traffic flows, signal patterns, and lane configurations. Designing a model that could generalize across such diverse conditions was a significant challenge. I learned that large-scale simulations require extensive runtime, and managing computational resources and deadlines was critical to success. Lastly, this project strengthened my real-world problem-solving ability and reinforced the importance of scalability and time management in applied AI research.

Contribution:
- Team Members: Erin Gregoire & Daniel Viola
- My Role: Developed the SARSA agent from scratch, implemented and fine-tuned the PPO agent, assisted development of Q-Learning & DDQN agents, and evaluated the single intersection environment
