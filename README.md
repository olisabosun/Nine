# Nine

Nine is a small AI agent project built around a first agent called computing-historian.

## Computing-Historian Agent

The computing-historian agent is the first AI agent in this project. It is set up to answer prompts through Azure AI Projects and a hosted agent reference named computing-historian.

### What it does

- Connects to an Azure AI Project endpoint.
- Uses the Azure OpenAI client exposed through the project client.
- Sends user prompts to the computing-historian agent reference.
- Prints the agent response in the terminal.

### Project files

- [agent.py](agent.py) runs the prompt loop and calls the agent.
- [README.md](README.md) describes the project and how the agent is used.

### How to run

1. Install the Python dependency:

```bash
pip install azure-ai-projects>=2.0.0
```

2. Update the Azure project endpoint in [agent.py](agent.py).

3. Run the script:

```bash
python agent.py
```

4. Enter a prompt when prompted. Type `quit` to exit.

### Notes

- The agent name is `computing-historian`.
- The current version reference in the sample is `1`.
- Keep Azure credentials and endpoints out of the README if you publish the repository publicly.
