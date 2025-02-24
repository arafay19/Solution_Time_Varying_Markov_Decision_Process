Time-Varying Markov Decision Processes (TVMDP)
This repository provides resources and documentation for the Time-Varying Markov Decision Process (TVMDP), a framework designed for decision-making in dynamic environments where state transitions and rewards vary over time. The work is based on the research paper by Lantao Liu and Gaurav S. Sukhatme, titled "A Solution to Time-Varying Markov Decision Processes".

Background
Traditional Markov Decision Processes (MDPs) assume static state transitions, which are insufficient for dynamic environments like underwater robotics or aerial navigation. The Time-Varying Markov Decision Process (TVMDP) extends MDPs to handle environments where state transitions and rewards vary over time. This framework is particularly useful for applications in marine robotics, autonomous vehicles, and other domains with spatiotemporal dynamics.

Key Concepts
Limitations of Traditional MDPs
Static Transition Models: Traditional MDPs assume time-invariant transition probabilities, which fail to capture dynamic environmental changes.

Variants: Discrete-Time MDP (DTMDP), Semi-Markov Decision Process (SMDP), Partially Observable MDP (POMDP), and Time-Dependent MDP (TDMDP) have limitations in handling time-varying dynamics.

Time-Varying Markov Decision Process (TVMDP)
Key Idea: Incorporate time-varying transition probabilities and rewards.


Two-Dimensional Value Propagation: Combines spatial (Bellman backup) and temporal (Kolmogorov equations) propagation.

Applications
Marine Robotics
Underwater Gliders: Navigating through dynamic ocean currents.

Autonomous Vehicles: Adapting to changing wind conditions or traffic patterns.

Other Domains
Aerial Vehicles: Path planning in dynamic wind conditions.

Robotics: Decision-making in environments with time-varying disturbances.

References:
Lantao Liu and Gaurav S. Sukhatme. "A Solution to Time-Varying Markov Decision Processes". IEEE Robotics and Automation Letters, 2018.

Boyan and Littman. "Exact Solutions to Time-Dependent MDPs". Advances in Neural Information Processing Systems, 2000.

Sutton and Barto. "Reinforcement Learning: An Introduction". MIT Press, 1998.
