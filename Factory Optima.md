# Intro
[[Cloud-based information infrastructure|Web-based]] SW platform for design and optimization of manufactuirng systems. It allows manufacturing process engineers (and their teams) to hierarchically compose, optimise and perform trade-off analysis of manufacturing [[Service networks]] based on a [[Industry Knowledge Base|Reusable repository]] of [[Performance Models]].

The key novelty and uniqueness is to enable the creation of modular, composable and reusable [[Modular simulation and modelling|simulation-like predictive models]], yet to achieve the performance of [[MP solvers vs Simulation-Base Optimization|MP solvers]] through symbolic analysis of simulation code to machine-generate MP models that are optimised using [[MP solver]].

The key novelty and uniqueness of Factory Optima is in its ability to perform optimisation and trade-off analysis on an arbitrary user-composed service network without the need to manually craft mathematical programming models, all while achieving the quality of optimisation results and computational efficiency of mathematical programming solvers, which significantly outperform simulation-based solvers.

Factory Optima as been demostrated through the applicaiton to the design anf optimization of the manufacturing process and supply chain for a [[Heat Sink SN use case|heat sink]]

# backgrund
It is based on:
 - The Unit Manufacturing Process (UMP) information model [[Bernstein, Lechevalier, and Libes 2018]] [[ASTM International 2016]], a standard representation of process models designed for reusability. 
 - a software architecture reported in [[Brodsky et al. 2016a]]  for (1) teh devleopment a reusable repository of UMP performance models and (2) their analysis and optimisation using the Unity Decision Guidance Management System ([[Unity DGMS]]). 
 -  [[Brodsky et al. 2017]] enables hierarchical composition of service networks based on a reusable model repository for (1) production services, such as manufacturing processes, assembly and inspection and (2) contract services, such as vending, manufacturing, packaging, repair and transportation. 
 
However, to compose such service networks and to perform analysis, [[Brodsky et al. 2017]] provided a low-level Integrated Development Environment (IDE) user-interface. Such an interface is not suitable for end users such as process engineers and operators, who do not have a software development background. Lifting this limitation is exactly the focus of Factory Optima.

# Next Steps
- for now the Web-interface for Factory optima is still form-based.  It would be important to move to a graphical user interface that uses and block diagramm tpye lenguage in order to improve user experience and lower barrier to entry.
- Create data and PMs Industry KB and Marketplace.
 > realisation of a shared and open UMP repository to support smart manufacturing activities across both industry and academia (Bernstein et al. 2016)
- Use ML to derive PMs form simulation and experimental data.
 > automated translation of standard static UMP representations, as shown in ASTM E3012–16 (ASTM International 2016), towards operational code in the form of functional models, such as the UMP PMs presented throughout this paper.
- Integration with other system to manage manufacturing data, modelling, digital artefacts
 > integrating system affordances with other applications curating product and process specific data, e.g. manufacturing execution systems, enterprise resource planning software and shop floor streams as described in (Helu and Hedberg 2015)
- Uncertinaty quatification.


# References
[[Brodsky 2019]]
