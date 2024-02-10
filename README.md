# LangChain_LLM_Application_Development
Notes, workbooks and summary of LangChain_for_LLM_Application_Development

LangChain - open source development framework for building LLM applications,
has modular components.

## Components

### Models
- Many integrations (20+)
- Text embedding Models, Chat models

### Prompts
- templates
- output parsers (5+)
- Example selectors

### Indexes 
- ways to ingest data, to combine with models.
- Document loaders,
- Text Splitters,
- Vector Stores and
- Retrievers.
### Chains 
- more end to end use cases
- -> combination of Prompt + LLM + Output parsing
- -> potential building blocks for longer chains
### Agents
- type of end to end use case, using the model as a reasoning engine.
- Agent Types ->Algos for getting LLMs to use tools.
- Agent Toolkits - agents paired with specifc tools for a specific task


# Models, Prompts and Parsers
Why use a prompt template rather than an F string? -> Same reason we use functions.
Covered langChain prompt templates libraries and built in prompts.
Library is great re parsers.
Also - ReAct - Chain of reasoning templates. (give space to think)
Use the key words
Thought:
Action:
Observation: 
Then they can be coupled with a parser to extract the text, tagged with those key words.
Ie to correctly specify the input, and output....


# Memory


# Chains


# Question and Answer


# Evaluation 


# Agents
