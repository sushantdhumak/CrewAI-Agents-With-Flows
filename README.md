# CrewAI Agents With Flows

Welcome to the CrewAI with Flow project, powered by [crewAI](https://crewai.com). This is to set up a multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable the agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

This project, courtesy of CrewAI, demonstrates the seamless integration of Agentic workflows with traditional Python procedures and functions. Through a straightforward example, it showcases how to combine these elements into a cohesive and efficient workflow. Specifically, this project leverages CrewAI Flows to create a structured, event-driven workflow that connects multiple tasks and manages state, illustrating the potential for building sophisticated AI automations.


## Understanding Your Crew

The poem-flow Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in the crew.


## Running the Project

To kickstart the crew of AI agents, flow and begin task execution, run this from the root folder of your project:

python .\poem_flow\src\poem_flow\main.py

This command initializes the poem-flow Crew, assembling the agents and assigning them tasks as defined in the configuration. This will run the create a `poem.txt` file with the output.
