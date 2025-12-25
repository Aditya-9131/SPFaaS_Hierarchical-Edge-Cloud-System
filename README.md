# SPFaaS_Hierarchical-Edge-Cloud-System.
 
SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System

This repository contains the simulation environment and implementation of the SPFaaS (Service Provisioning and Request Scheduling for FaaS) framework. SPFaaS is designed to optimize service placement and request scheduling in hierarchical edge-cloud architectures under a Function-as-a-Service (FaaS) paradigm.

Below is the suggested content for the README.md file for your GitHub repository. This content is based on the technical details and results presented in your research paper.

-SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System

This repository contains the simulation environment and implementation of the SPFaaS (Service Provisioning and Request Scheduling for FaaS) framework. SPFaaS is designed to optimize service placement and request scheduling in hierarchical edge-cloud architectures under a Function-as-a-Service (FaaS) paradigm.

-Overview
The geographical distance between centralized cloud data centers and users creates latency obstacles for modern applications. SPFaaS addresses this by utilizing a collaborative, hierarchical organization of edge nodes (leaf nodes), peer nodes, and a root cloud server.

Below is the suggested content for the README.md file for your GitHub repository. This content is based on the technical details and results presented in your research paper.

SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System

This repository contains the simulation environment and implementation of the SPFaaS (Service Provisioning and Request Scheduling for FaaS) framework. SPFaaS is designed to optimize service placement and request scheduling in hierarchical edge-cloud architectures under a Function-as-a-Service (FaaS) paradigm.

-Key Contributions
Hierarchical Collaboration: A system architecture where edge nodes coordinate with peers and parent nodes to serve requests.

Effective Provisioning: A bottom-up service provisioning strategy that avoids redundant service hosting by checking the active pools of child and peer nodes.

Optimized Scheduling: Implementation of the Earliest Deadline First (EDF) policy to prioritize latency-sensitive tasks.

Proven Performance: Experimental results show a 41% increase in served requests compared to state-of-the-art approaches and performance close to the optimal centralized strategy.


SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System

This repository contains the simulation environment and implementation of the SPFaaS (Service Provisioning and Request Scheduling for FaaS) framework. SPFaaS is designed to optimize service placement and request scheduling in hierarchical edge-cloud architectures under a Function-as-a-Service (FaaS) paradigm.

-Overview
The geographical distance between centralized cloud data centers and users creates latency obstacles for modern applications. SPFaaS addresses this by utilizing a collaborative, hierarchical organization of edge nodes (leaf nodes), peer nodes, and a root cloud server.

-Key Contributions
Hierarchical Collaboration: A system architecture where edge nodes coordinate with peers and parent nodes to serve requests.

Effective Provisioning: A bottom-up service provisioning strategy that avoids redundant service hosting by checking the active pools of child and peer nodes.

Optimized Scheduling: Implementation of the Earliest Deadline First (EDF) policy to prioritize latency-sensitive tasks.

Proven Performance: Experimental results show a 41% increase in served requests compared to state-of-the-art approaches and performance close to the optimal centralized strategy.

-System Architecture
The system consists of three main modules:

Request Acceptance: Checks if a requested service is in the local active pool, peer pool, or parent pool while ensuring the deadline can be met.

Service Provisioning: Periodically updates the "active pool" of services at each node based on hit/miss frequencies.

Request Scheduling: Orders accepted requests to maximize the success rate (percentage of requests finished before their deadline).

Below is the suggested content for the README.md file for your GitHub repository. This content is based on the technical details and results presented in your research paper.

-SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System
This repository contains the simulation environment and implementation of the SPFaaS (Service Provisioning and Request Scheduling for FaaS) framework. SPFaaS is designed to optimize service placement and request scheduling in hierarchical edge-cloud architectures under a Function-as-a-Service (FaaS) paradigm.

-Overview
The geographical distance between centralized cloud data centers and users creates latency obstacles for modern applications. SPFaaS addresses this by utilizing a collaborative, hierarchical organization of edge nodes (leaf nodes), peer nodes, and a root cloud server.

-Key Contributions
Hierarchical Collaboration: A system architecture where edge nodes coordinate with peers and parent nodes to serve requests.

Effective Provisioning: A bottom-up service provisioning strategy that avoids redundant service hosting by checking the active pools of child and peer nodes.

Optimized Scheduling: Implementation of the Earliest Deadline First (EDF) policy to prioritize latency-sensitive tasks.

Proven Performance: Experimental results show a 41% increase in served requests compared to state-of-the-art approaches and performance close to the optimal centralized strategy.

-System Architecture
The system consists of three main modules:

Request Acceptance: Checks if a requested service is in the local active pool, peer pool, or parent pool while ensuring the deadline can be met.

Service Provisioning: Periodically updates the "active pool" of services at each node based on hit/miss frequencies.

Request Scheduling: Orders accepted requests to maximize the success rate (percentage of requests finished before their deadline).

-Simulation Setup
The simulation is implemented in C++ with the following default parameters:

Network Topology: Binary tree hierarchy.

Active Pool Size: 150 services per edge node.

Service Types: 1,000 unique services.

Provisioning Epoch: 10 seconds.

Propagation Delays: 5ms (peer), 10ms (parent), 60ms (cloud). 

-Experimental Results
The framework was validated using both synthesized and real-world datasets (Spotify track charts from Kaggle).

Synthetic Data: Outperformed decentralized approaches by 47%.

Real-world Data: Beat state-of-the-art coordinated approaches by 17% and decentralized approaches by 67%.

-Citation
If you use this code or the SPFaaS strategy in your research, please cite:
Harshwardhan Dubey, Manojit Ghose, and Aryabartta Sahu. "SPFaaS: Service Provisioning and Request Scheduling in a Hierarchical Edge-Cloud System under Function-as-a-Service Framework." 2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT). IEEE, 2024.



