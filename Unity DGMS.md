Unity DGMS is an integrated analytics platform that aims to simplify the development of intelligent, decision-making systems [[Nachawati 2017]]. 

A key technical challenge in realising a system based on this architecture lies in developing specialised algorithms that automatically translate a uniform, high-level representation of a performance model into the low-level, specialised models required by each of the underlying tools.
The solution to this challenge is based on the Unity DGMS, which provides support for different methods of analysis, including optimisation and Pareto-optimal trade-off analysis, without the need to manually develop specialised models for low-level tools such as mathematical programming solvers. Within Unity DGMS, the Unity analytics engine provides several core analytical operators that can be performed against models in the repository. The implementation of these core analytical operators, which include but are not limited to computation, prediction, learning, simulation and optimisation, involve compilation, symbolic computation and reduction techniques, as well as specialised optimisation and learning algorithms

To overcome these limitations, the architecture is augmented with Unity DGMS as a middleware layer, situated between the applications layer and the low-level tools layer in the diagram in Figure 12. 

Then, Unity DGMS performs automatic translation of the high-level performance models into a lower-level optimisation model expressed in the modelling language AMPL https://ampl.com/



