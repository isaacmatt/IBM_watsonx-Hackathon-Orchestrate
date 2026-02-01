# IBM_watsonx-Hackathon-Orchestrate
An end-to-end workflow where a resident submits a road damage report with a photo, the system classifies and prioritizes the issue, routes it for human approval, integrates with a city work order system, and provides status updates back to the resident. Entry for the AI Agent Category using an agent swarm approach. 
This project contains restricted components within watsonx Orchestrate as granted access by IBM for hackathon participation.
Two agents were created with the goal of testing an initial assessment and emergency incident isolator considered the Welcome agent, within an agent that collects user contact information.
The second agent, called the Routing agent was created to sort using the routing table uploaded here to a follow-up agent representing a separate entity who can manage its own operations.
A third agent was created to test independant entities operating outside of the initial, Welcome agent that represents external departments handling their own database of operations and having calls routed to them.
This agent was called the Transportation Ops Agent which is a Transporation Department simulated data collector and incident manager.
Additional agents were not created but would be theoretically used as part of a multidepartmental and multiagent run architecture.
