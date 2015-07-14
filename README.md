# LoadAggregator
###A BPEL project for Web Information Systems
*University of Thessaly*

Here is the implementation of the orchestration of two web services. Each service 
simulates an electrical appliance running on a local server and producing a load demand, an 
information which is being aggregated by the Business Process into a mean load demand.

The ultimate goal was to consume the Business Process output on GridLab-D which proved to be
more difficult then it sounds due to the difficulty of producing a working client through 
either STAFF or gSOAP framework.

None the less the provided code works like a charm and that is thanks to the unseen, but not unsung, 
heroine of the WIS class Antonia Nasiakou who produced the implemented services and assisted me 
on the project.

My setup: 

  * Apache Ode BPEL engine
  * Apache Tomcat 6.0  Application Server
  * Eclipse Helios
  * BPEL Designer pluggin for Eclipse
