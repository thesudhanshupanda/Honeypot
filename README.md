# Honeypot
T-Pot is an all-in-one, open-source honeypot platform designed to simplify the deployment and management of multiple honeypots for network security monitoring and threat intelligence gathering. Here are some key aspects of T-Pot:

Key Features 
************
Multiple Honeypots: T-Pot includes a wide range of pre-configured honeypots like Cowrie, Dionaea, ElasticHoney, and many more.

Visualization: Utilizes the Elastic Stack for data visualization and provides animated live attack maps.

Containerization: Each honeypot and tool runs in its own Docker container for isolation and easy management.

Centralized Management: Offers a unified interface to configure, monitor, and manage multiple honeypots.

Threat Intelligence: Collects and aggregates valuable data on attacker behavior and tactics.

Logging and Analysis: Generates detailed logs and captures network traffic for in-depth analysis.


Architecture
************
T-Pot is built on a Debian operating system and uses Docker and docker-compose to run multiple honeypots and tools simultaneously. Its modular design allows for easy extension with additional components.