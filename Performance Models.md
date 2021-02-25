Performance Models (PM) formally describe process feasibility constraints and metrics of interest, such as cost, throughput and CO2 emissions, as a function of fixed and control parameters, such as equipment and contract properties and settings.  A PM provides an analytical function that computes the metrics as a function of the fixed parameters and control parameters subject to feasibility constraints

PMs can represent:
- [[Unit Manufacturing Process]] such as cutting, welding or drilling. 
- base contract services (furniture of materials or components, outsourcing of activities )
 - composite service network.

PMs for the base services can be composed hierarchically to model the  [[Service networks|service network]]. Unity DGMS assembles the PMs of each subproces to create the PM of the Service Network.  This can then be used to pose what-if questions, optimising activity-specific parameters to meet some global objectives and incorporating advanced analytics 

The key concept each activity can be represented as a PM which can be resused, modified and composed hierarchically to model very complex manufacturing processes and supply chains. The uniqueness of this solution is that it decouples analytical models from the various kinds of analysis that can be performed on them. 

This provides a uniform, high-level abstraction over different low-level tools and is key in supporting the optimisation and trade-off analysis of manufacturing and contract service networks. The consistent representation across different manufacturing stages offers engineers a reusable toolbox to evaluate process designs and plans and lowers the barrier to access such analysis for domain experts, e.g. process engineers and operation managers.

In order to perform the analytic functions, the PMs need to be instantiated in specific project and calibrated for the specific applicaiton. (object orient approach, use of liobraries of PM classes)

