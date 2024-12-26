# Event Management AI Crew

This project implements an AI-powered event management system using the CrewAI framework. The system automates various aspects of event planning and execution through a team of specialized AI agents.

## Features

- Venue Coordination: Identifies and books appropriate venues based on event requirements
- Logistics Management: Handles catering, equipment, and other logistical aspects
- Marketing and Communications: Promotes the event and engages with potential attendees
- Task Automation: Executes tasks asynchronously and generates structured outputs
- Integration with External Tools: Utilizes web scraping and search capabilities

## How It Works

1. The system initializes three AI agents: Venue Coordinator, Logistics Manager, and Marketing and Communications Agent
2. Each agent is assigned specific tasks related to their expertise
3. The agents use tools like web scraping and search to gather necessary information
4. Tasks are executed either synchronously or asynchronously as specified
5. Outputs are generated in various formats, including JSON and Markdown
6. The crew coordinates the efforts of all agents to plan and manage the event

## Tech Stack Used

- CrewAI
- LangChain
- OpenAI GPT-3.5 Turbo
- Serper API
- Pydantic
- Python
- Dotenv


## Note

This project requires valid API keys for OpenAI and Serper to function properly. Ensure you have the necessary credentials before running the application.


