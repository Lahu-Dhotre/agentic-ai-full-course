# Agentic AI Full Course

This repository contains a practical, hands-on collection of Jupyter notebooks focused on building and experimenting with agentic AI workflows. The material covers core concepts such as creating an agent, customizing behavior, working with multiple agents, and generating structured outputs.

## Repository structure

- `agentchat/` — beginner notebook for creating and interacting with a first AI agent
- `agentcustomization/` — examples for customizing agent behavior and configuration
- `multi_agents/` — notebooks exploring multi-agent collaboration and coordination
- `structured_output/` — examples for producing structured and machine-readable outputs
- `autogen-env/` — environment and first AutoGen agent examples
- `requirement.txt` — Python dependencies for the project

## Getting started

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On Windows: .venv\Scripts\activate
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirement.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the notebooks in the folders above and run them in order.

## Suggested learning flow

- Start with `agentchat/agent_chat_first_agent.ipynb`
- Explore `agentcustomization/agent_chat_first_agent.ipynb`
- Move into `multi_agents/understanding_multi_agents.ipynb`
- Review `structured_output/structured_output.ipynb`

## Notes

- Some notebooks may require environment variables or API keys depending on the framework or model provider used.
- If a notebook fails because a package is missing, reinstall the dependencies from `requirement.txt`.

## License

This project is provided for educational purposes.
