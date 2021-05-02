# Simulation
  - Imitation of the operations of a real-world process or system over time using a computer program
  - Generation of an artificial history of a system
  - Observation of the artificial history to deal with the operating characteristics of the real system

# Simulation can be used as
  - Design tool for predicting and optimizing the performance of new systems
  - Analysis tool for predicting the effect of changes to existing systems

# System
  - A group of objects or collection of entities that act and interact together towards the accomplishment of some logical ends.

# Entity
Any object or component in the system which requires explicit representation in the model, e.g., a server, a customer, a machine
  - Attribute is a property of entity.
  - Attributes are represented by state variables

# Activity
Duration of known length, e.g. check balance at the bank, serve acustomer.
  - Activities form part of the model specification

# State of a system
Collection of variables and their values necessary to describe the system at a particular time.
  - Schedule activities, output performance e.g. time of arrival of each customer into the bank.

# Discrete System
State variables change instantaneously at separate points of time. e.g Bank Model: State change occurs only when a customer arrives or departs.

# Continous System
State variables change continoulsy as a function of time E.g Airplan fligh: state variables like postion, velocity change contnously.

# Model
Model is a Representation of an object, a system, or an idea in some form other than that of the entity itself.
  - Model is a simplified representation of a real system.
  - Modelling isthe process of representing a system with a specific tool to study its behaviour

# Model is used to:
  - Study systems in the design stage before such systems are built
  - Study potential changes to the system and predict their impact
  - Get answers for “What-if” questions

## Physical models are the models whose physical characteristics resemble those of the system being modeled. It looks or feels like the real thing.
## Mathematical model uses symbolic notation and mathematical equations to represent a system.

# Simulation Model vs. Analytical Model
Use analytical model whenever possible. Simulation does not require that many simplifying assumptions.
  - Use simulation when:
  - Complete mathematical formulation does not exist or an analytical solution cannot be developed;
  - Analytical methods are available, but the mathematical procedures (Partial differential equations) are so complex that simulation provides a simpler solution;
  - Modelling complex dynamic systems theoretically needs too many simplifications and the emerging models may not be therefore valid;
  - Simulations are often complex error-prone pieces of software.
  - Simulation can take a LONG time to execute
  - Simulation only produces approximate answers
  - Analytical models are less flexible, but they are exact and efficient

# Performance Measures: 
  - Performance: Capability of a system to perform a certain task Characterized by certain performance measures depending on the type of the system under study
  - Performance Measures: Characteristics of the system with which the system performance is quantified e.g., delay and response time in a queueing model
  - For example: maximum, minimum, totals, mean, variance, service times, lengths of queues, loss rates, etc.

# Advantages of Simulation
  - Study new designs without needing extra resources
  - Study new designs without interrupting real systems
  - Improve understanding of system
  - Determine important interaction of variables and the importance of variables on the system performance
  - Verify analytic solutions
  - Time can be compressed or expanded allowing for speedup or slowdown of the phenomena under consideration
  - It is an effective tool for training and education (flight simulators to train pilots)
  - Less dangerous and less expensive

## Most operational models are stochastic ,dynamic, and discrete, therefore will be called discrete-event simulation models

# Deterministic Simulation
  - No probabilistic component or random variable in the system
  - Have a known set of inputs
  - Example: deterministic arrivals would occur at a dentist’s office if all patients arrived at the scheduled appointment time
 
# Stochastic Simulation
  - Has one or more random variables as inputs
  - Random inputs lead to random outputs
  - Random outputs are estimates of the true characteristics of a model Example: Queuing systems

# Static Simulation
  - Time plays no role
  - Represents a system at a particular point of time
  - Represents the system at a particular point in time
  - Example: Monte Carlo Method, calculating value of Pi

# Dynamic Simulation
  - Represents a system as it evolves over time
  - Exemple: Simulation of a Bank from 9:00 A.M. to 4:00 P.M.

# Discrete Simulation
  - The state variable(s) changes only at discrete points in time.
  - Example: Queuing system of a bank

# Contnous Simulation
  - The state variable(s) changes continuously 
  - Example: the head of water behind a dam.

# Important links
  - M/M/1 Queue Simulator: https://github.com/thanujann/Queue-Simulator
  - Poissons distribution (Queuing theory): http://web.tecnico.ulisboa.pt/mcasquilho/acad/or/queue/SBakerQueuingI.pdf
  - Random number generation using inverse transform techinique: https://math.stackexchange.com/questions/28004/random-exponential-like-distribution
  - Markov chains and queueing theory: https://www.math.uchicago.edu/~may/VIGRE/VIGRE2011/REUPapers/Constantin.pdf
  - Stationary distribution and performance measure of M/M/1 Queue: https://people.maths.bris.ac.uk/~maajg/teaching/iqn/queues.pdf
  - Discrete event simulation: https://www.cs.bu.edu/faculty/matta/Teaching/cs655-papers/shankar-des.pdf
  - Multi server system with T-limited service https://core.ac.uk/download/pdf/144443021.pdf
  - Linear Congruential Generator: https://www.value-at-risk.net/linear-congruential-generators/
  - Simulation of Single-Server Tandem Queueing Model: http://emis.impa.br/EMIS/journals/HOA/IJSA/Volume10_4/381.pdf


  
