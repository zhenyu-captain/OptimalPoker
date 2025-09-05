Bringing Solvers Closer to Real Gameplay with Folded-Range Simulation

A More Realistic Simulation
Introduce card removal effects from folded player ranges to make your analysis more accurate.

What is the Bunching Effect?
In real games, most players fold weak hands, which means the remaining players are more likely to hold stronger ones. The Bunching Effect is designed to simulate this card-removal impact caused by folded ranges.

Key Features
Supports up to 4 folded players (ideal for 6-max scenarios)
Enter folded player ranges and run a precomputation to account for the effect
Exact simulation without abstractions or approximations, ensuring results that better reflect real gameplay

Important Notes
Enabling this option will significantly increase computation load and slow down the solver
Recommended only when high-precision simulation is required; if unsure, leave it disabled
