# Intro
The manufacturing activity is represented as a network of service-oriented components that are linked together to produce products or Product/Service Systems (PSS) to meet some specified demand.  The service network can represent production cells, lines, factory facilities and supply chains

Example: [[Heat Sink SN use case]]

The service network is hierarchically conposed of subprocesses which in turn can be decomposed untill we get to the lower level of the hierarchy where we find atomic processes or unit processes which cannot be furher decomposed. 


The following terms are used to describe the various components of a service network.
- **Vendor**: describing an organisation that provides a finished product, e.g. raw material, bar stock or fully realised components, at some cost.
- **Contract Manufacturer**: describing an organisation that provides a manufacturing service, e.g. precision welding, mould-making and precision machining, at some cost.
- **Internal Manufacturer**: describing an internal activity ‘controlled’ by the original equipment manufacturer (OEM) of the PSS.
- **Production Line**: describing a chain of Internal Manufacturer activities. It is assumed that a production line is also ‘controlled’ by the OEM.

The Service Network and it's base service components are carachterized by their [[Performance Models]] which enable to perform advance analytics functionalities such as verification of production targets and requirements against requirements,  parameters optimization and trade studies, decision support.

# References
The idea of invoking composite services to form a network of services in a programmatic way through web services was discussed in (Menasce 2004a). This along with the work in (Menasce 2004b) discuss how global performance metrics can be computed when analyzing a network of services. The structure of the network and the specific performance characteristics of individual services, specified in terms of contracts, are necessary to compute composite performance metrics. 


