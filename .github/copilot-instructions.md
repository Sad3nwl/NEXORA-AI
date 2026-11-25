
# NEXORA AI - Copilot Instructions

## Project Overview
NEXORA AI is a multi-agent system for early operational
risk detection, incident investigation, prediction,
and decision support in IT service operations.

## Technology Stack
- Python
- Pandas and NumPy
- Scikit-learn / XGBoost
- LangGraph
- FastAPI
- PostgreSQL
- React + TypeScript

## Development Rules
1. Follow the existing repository structure.
2. Write modular and reusable code.
3. Use type hints in Python.
4. Add docstrings to important functions.
5. Handle missing and invalid data.
6. Never hardcode API keys or credentials.
7. Add tests for important functionality.
8. Do not invent dataset columns or labels.
9. Validate data before building predictive models.
10. Keep ML predictions separate from LLM explanations.

## Agent Rules
- Each agent must have a clearly defined responsibility.
- Agents must return structured outputs.
- The Orchestrator coordinates the agents.
- High-impact actions require human approval.
- Agents must not invent evidence or incident records.

## Important
Do not claim that a model predicts SLA breaches
unless the dataset supports the required target
and evaluation has been completed.

