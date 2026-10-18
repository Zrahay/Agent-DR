# dr-agent

LLM/VLM agent that, given a MuJoCo task, automatically discovers randomizable
physics/visual parameters, proposes ranges, and empirically validates them.
Inspired by DrEureka (Ma et al., 2024).

## Setup
```
uv sync
```

## Run
```
uv run python -m dr_agent.loop
```
